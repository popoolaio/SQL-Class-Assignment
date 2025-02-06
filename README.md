# SQL CLASS ASSIGNMENT
This repository contains the AdventureWorks database backup and SQL assignment instructions for trainees in the use of SQL for Data Analytics.


# Table of Contents

1. [Overview](#Overview)
2. [How to Use This Repository](#How to Use This Repository)
   

# Overview

Welcome to the SQL Class Assignment! This repository contains two files:

1. **AdventureWorks Database Backup** (AdventureWorksDB.bak) – A sample database used for SQL exercises.
2. **Assignment Instructions** (SQL_Assignment_Instructions.pdf) – A document detailing the tasks you need to complete.


# Introduction to the AdventureWorks Database
The AdventureWorks 2017 database is a sample database provided by Microsoft, designed to showcase the capabilities of SQL Server and related technologies. It simulates a fictional bicycle manufacturing company called Adventure Works Cycles, and contains data related to product management, sales, purchasing, employees, and more.

The database is composed of multiple schemas and tables, each representing different business entities. Its key schemas include:

- **Sales:** Information on customer orders, sales transactions, and sales territories.

- **Person:** Data about customers, employees, and contacts.

- **Production:** Information on products, bills of materials, and manufacturing processes.

- **Purchasing:** Details about vendors, purchase orders, and suppliers.

- **HumanResources:** Employee information, job roles, departments, and pay history.


# How to Use This Repository
## Step 1: Download the Files
- Click on the [AdventureWorksDB.bak file](https://drive.google.com/file/d/18spWji6pcRVclRdZZD7hIWBJ7tROiXXy/view?usp=sharing) and select **Download**.
- Click on [SQL_Assignment_Instructions.pdf](https://github.com/popoolaio/SQL-Class-Assignment/blob/main/SQL_Assignment_Instructions.pdf) and download it.

## Step 2: Restore the Database in SQL Server
- Copy the already downloaded **AdventureWorksDB.bak** file and drop it inside a folder named **Backup** by following this sequence: Double Click your **Local Disk** > **Program Files** > **Microsoft SQL Server** > **MSSQL16.MSSQLSERVER or MSSQL22.MSSQLSERVER** > **MSSQL** > **Backup**. The sequence is the same as ***C:\Program Files\Microsoft SQL Server\MSSQL16.MSSQLSERVER\MSSQL\Backup***
- Open SQL Server Management Studio (SSMS).
- Connect to your SQL Server instance.
- Right-click on **Databases** in Object Explorer and select **Restore Database**... to launch the Restore Database wizard.
- Select **Device** and then click ellipses **(...)** to choose a device.
- Select **Add** and then choose the **AdventureWorksDB.bak** file you recently moved to the backup location.
- Select **OK** to confirm your database backup selection and close the Select backup devices window.
- Check the Files tab to confirm the Restore as location and file names match your intended location and file names in the Restore Database wizard.
- Click **OK** to restore the database successfully.

## Step 3: Complete the Assignment
- Open the **SQL_Assignment_Instructions.pdf** file.
- Follow the instructions to complete the SQL queries and tasks.
- Test your queries using the restored AdventureWorks database.
- Submit your answer (SQL Query file) by uploading it to the dedicated online storage, as indicated in the instruction document.
- Good luck.
