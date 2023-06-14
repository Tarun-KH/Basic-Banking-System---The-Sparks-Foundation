# Sparks Foundation - Basic_Banking_System

## Index
- [Description](#Description)
- First Time Installation
- How To Run
- Screenshort

## Description
- This a Internship task by The Sparks Foundation.
- This project is built on HTML/CSS, Bootstrap, PHP and MySQL(XAMPP server).
- Details of Customers are maintained as `UserName`, `E-mail`, `Balance` are fields.
- Transaction is done through PDO, If some Error occured while Transaction changes made to table is Rollback(Reverted).  

## First Time Installation
- Clone the Repository.
- Make sure you have installed XAMPP on your computer.
- Copy this folder(Basic_Banking_System) to XAMP installation Directory and then inside htdocs folder.

```
For Example
C:\xampp\htdocs\
```
- Open Xampp Control Panel. Click on Start button near Apache and MySQL.Once the successfull running of Apache and Xampp, click on admin its take to pHpMyAdmin page there import user SQL database file(i.e Bank_of_India.sql file).
- After importing all files successfully.
- Open browser type the following into search bar.
```
http://localhost/Basic_Banking_System/
```

## How To Run
- After following steps above(First Time Installation).
- Make Sure XAMPP is active with Apache and MySQL Server Enabled.
- Open Browser Enter the following URL:
```
http://localhost/Basic_Banking_System/
```
OR
```
http://localhost/Basic_Banking_System/index.php
```
- You will land to Homepage of Bank of India Website.
- Click On `New User for Registration` which Navigates to Resgister Page. If your already registered click on Make Transaction for Transactions.
- You will see Customer details in table with deatils like(Name, Email, Current balance, etc.).
- Click on `Send` Button Corresponding any row of table.
- Now We are on Money Transfering Page. Now select a Valid Name in `Send Money To` textbox and also Enter Amount, Click on `Send` Button To Start Transfer.
- Make sure the Amount you enter is not greater then current balance of the Person Selected, else it will pop Message.
- If the Transaction is successful Message will displayed and Changes made by above Transaction will be updated to customer table. 
- Click On Transaction Histroy Button in home page or in navigation bar to see the Recent Transaction Histroy.