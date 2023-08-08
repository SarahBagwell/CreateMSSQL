<h1>CREATE Statements</h1>

<h3>Description</h3>
Sample CREATE statements based on a provided ERD from instructor. These statements include constraints, primary and foreign keys, and data types. 
<br />
<h3>Entity Relationship Diagram:</h3>
<img src="https://i.imgur.com/13vulYw.png" height="80%" width="80%" alt="Provided ERD"/>
<h3>CREATE Statements</h3>
<p>
CREATE TABLE Employee_SB </br>
(Employee_ID	varchar(5) Not Null, </br>
	Employee_Name		  varchar(30), </br>
	Employee_Address	varchar(50), </br>
	City			        varchar(30), </br>
	State			        varchar(2), </br>
	Postal_Code		    varchar(5), </br>
CONSTRAINT employee_sbPK	PRIMARY KEY (Emplyoee_ID)); </br>  
</p>
<p>
  CREATE TABLE Project_SB </br>
(Project_ID		varchar(5) Not Null, </br>
	Project_Name 	      varchar(30), </br>
	Project_Start_Date	date, </br>
CONSTRAINT project_sbPK		PRIMARY KEY (Project_ID)); </br>
</p>
<p>
CREATE TABLE Billing_SB </br>
(Billing_ID		varchar(5) Not Null, </br>
	Billing_Rate	decimal(5,2),	</br>
CONSTRAINT billing_sbPK 	PRIMARY KEY (Billing_ID)); </br>
</p>
