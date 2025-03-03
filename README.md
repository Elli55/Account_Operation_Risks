# Power BI Transaction Analysis Dashboard

## Overview
This project focuses on analyzing transactional data using Microsoft SQL Server and Power BI. The process begins with bulk data insertion into MSSQL, followed by initial data exploration using SQL-based algorithms. Once the primary insights are derived, the transaction data is refined and structured within Power BI for further analysis.

## Steps Involved

### 1. Data Preparation in MSSQL
- The dataset is initially imported into MSSQL using the BULK INSERT function.
- Various SQL queries and transformations are applied to clean and preprocess the data.
- Key algorithms are used to identify patterns and trends before visualizing the data in Power BI.

### 2. Data Processing in Power BI
- After the SQL-based analysis, all further transformations and adjustments are performed directly within Power BI using Power Query.

### 3. Dashboard Structure
The Power BI report consists of two primary screens:

#### **Screen 1: User Account Transactions**
- Displays the number of accounts associated with a given user ID.
- Allows selection of a specific account to view key transaction details, including:
  - Amount transferred
  - Recipient information
  - Time-based filtering of transactions
- Identifies and displays error codes related to the user's transactions.

#### **Screen 2: Account Activity Analysis**
- Provides a detailed breakdown of a selected account:
  - Number of login attempts
  - Frequency of errors encountered
  - Login history with IP address tracking
- Categorizes the user's activity into a **risk level classification** based on system-defined parameters.
- Helps form an **initial impression of the account's behavior**, aiding in determining which department should be consulted for further details.

## Key Insights
- The dashboard provides real-time monitoring of transactional activities and account behavior.
- It enables fraud detection by identifying suspicious activities.
- Error tracking allows for efficient troubleshooting and proactive resolution of system issues.

