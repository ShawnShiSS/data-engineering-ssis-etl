# Data Engineering - Build an ETL pipeline using SSIS
This project provides a starting point for building an ETL pipeline using SQL Server Integration Services (SSIS) in Visual Studio 2019.

# Goals
The primary goal of the project is to provide a basic solution for anyone who is building a new ETL pipeline using SSIS.

# Getting Started
Prerequisites
* Visual Studio 2019 installed. Note Visual Studio 2017 works slightly different regarding SSIS and this article may not work exactly for Visual Studio 2017.
* SQL Server already installed.

SSIS package encryption password
- The package is configured to encrypt sensitive information by password, instead of using User Key.
- The password is: password
- For more details on encryption with User Key vs with password, please see my article: https://medium.com/@ss.shawnshi/data-engineering-how-to-address-ssis-package-failed-to-decrypt-protected-xml-node-for-password-264c9908f6e.

# Features supported
* Migrating data from one database on server#1 to another database on server#2.
* Addressed common error code 0x8009000B with message: Failed to decrypt protected XML node "DTS:Password" with error 0x8009000B
