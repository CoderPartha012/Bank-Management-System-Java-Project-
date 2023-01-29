# Bank-Management-System-Java-Project-
Bank Management System using Swing(Concept of Java), AWT, MYSQL Database
---------------------------------------------------
Database Queries for BANK MANAGEMENT SYSTEM Project
---------------------------------------------------

1 - Create database with name bankmanagementsystem in mysql

create database bankmanagementsystem;

2 - Select the database you just created

use bankmanagementsystem;

3 - Create our first Table in the selected database with name signup

create table signup(formno varchar(20), name varchar(20), father_name varchar(20), dob varchar(20), gender varchar(20),email varchar(30), marital_status varchar(20), address varchar(40), city varchar(25), pincode varchar(20), state varchar(25));

4 - Create the second table to store more information of user

create table signuptwo(formno varchar(20), religion varchar(20), category varchar(20), income varchar(20), education varchar(20), occupation varchar(20), pan varchar(20), aadhar varchar(20), seniorcitizen varchar(20), existingaccount varchar(20));

5 - Create the third table to store the account information of user

create table signupthree(formno varchar(20), accountType varchar(40), cardnumber varchar(25), pin varchar(10), facility varchar(100)); 

6 - Create the Login table to store login information

create table login(formno varchar(20), cardnumber varchar(25), pin varchar(10));

7 - Now create bank table to store transactions related information 

create table bank(pin varchar(10), date varchar(50), type varchar(20), amount varchar(20));
////////////////////////////////////////////////////////////////////////////
The “Bank Account Management System” project is a model Internet Banking Site. This site
enables the customers to perform the basic banking transactions by sitting at their office or at
homes through PC or laptop. The system provides the access to the customer to create an
account, deposit/withdraw the cash from his account, also to view reports of all accounts present.
The customers can access the banks website for viewing their Account details and perform the
transactions on account as per their requirements. With Internet Banking, the brick and mortar
structure of the traditional banking gets converted into a click and portal model, thereby giving a
concept of virtual banking a real shape. Thus, today's banking is no longer confined to branches.
E-banking facilitates banking transactions by customers round the clock globally.
The primary aim of this “Bank Account Management System” is to provide an improved design
methodology, which envisages the future expansion, and modification, which is necessary for a
core sector like banking. This necessitates the design to be expandable and modifiable and so a
modular approach is used in developing the application software.
Anybody who is an Account holder in this bank can become a member of Bank Account
Management System. He has to fill a form with his personal details and Account Number.
Bank is the place where customers feel the sense of safety for their property. In the bank,
customers deposit and withdraw their money. Transaction of money also is a part where
customer takes shelter of the bank. Now to keep the belief and trust of customers, there is the
positive need for management of the bank, which can handle all this with comfort and ease.
Smooth and efficient management affects the satisfaction of the customers and staff members,
indirectly. And of course, it encourages management committee in taking some needed decision
for future enhancement of the bank.
Now a day’s, managing a bank is tedious job up to certain limit. So software that reduces the
work is essential. Also, today’s world is a genuine computer world and is getting faster and faster
day-by-day. Thus, considering above necessities, the software for bank management has become
necessary which would be useful in managing the bank more efficiently.
All transactions are carried out online by transferring from accounts in the same Bank or
international bank. The software is meant to overcome the drawbacks of the manual system.
