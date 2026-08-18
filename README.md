# CLOUD-DATA-STORAGE-SERVER

CLOUD DATA STORAGE SERVER

REG NO : 212224230234

NAME : Sadhana S

AIM:

To create and configure an Amazon RDS MySQL DB instance with Multi-AZ deployment, connect it to a web application using a security group and DB subnet group, and perform CRUD (Create, Read, Update, Delete) operations on the database through the application.

ALGORITHM

Log in to the AWS Management Console.

Create a DB Security Group allowing MySQL (3306) access from the Web Security Group.

Create a DB Subnet Group with subnets in two Availability Zones.

Launch an Amazon RDS MySQL Multi-AZ DB instance.

Configure the DB instance with the required username, password, and database name. Wait until the database status becomes Available and copy the endpoint.

Open the provided web application using the Web Server IP.

Enter the RDS endpoint, database name, username, and password.

Connect the application to the database.

Test the application by adding, editing, viewing, and deleting records.

OUTPUT

<img width="1880" height="907" alt="image" src="https://github.com/user-attachments/assets/4c17e0ad-7018-4003-a81e-c5936af3cf85" />


<img width="1886" height="922" alt="image" src="https://github.com/user-attachments/assets/fd632e2b-b80b-4314-ae5c-a7ef7e766ca7" />


<img width="1887" height="925" alt="image" src="https://github.com/user-attachments/assets/a4be1277-9102-4d8c-947a-9e93cf3217c9" />


<img width="1451" height="572" alt="image" src="https://github.com/user-attachments/assets/8a1b4b26-32c7-4c45-85b0-cd35db31cc89" />


<img width="1811" height="880" alt="image" src="https://github.com/user-attachments/assets/78efca29-6055-425d-ae85-6e67a5232055" />


<img width="1495" height="910" alt="image" src="https://github.com/user-attachments/assets/9ead2f57-77d2-434d-b1d0-5b2c8f80d511" />


RESULT

The Amazon RDS MySQL Multi-AZ DB instance was successfully created and connected to the web application, and CRUD operations were performed successfully on the database.
