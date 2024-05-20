In this project we will do an end to end data analytics project using python and SQL. We will use Kaggle API to download the dataset and to data processing and cleaning using pandas and load the data into sql server. 
Lastly we will answer some interesting questions using SQL.
Here some of the questions are available in sql file with code,before that there is a small procedure for import data from excel to sql server
 Using SQL Server Management Studio (SSMS)
1. Open SSMS:
-Launch SQL Server Management Studio and connect to your SQL Server instance.

2. Open the Import and Export Wizard:
-Right-click on the database where you want to import the data.
-Go to Tasks > Import Data....

3. Choose a Data Source:
-In the Import and Export Wizard, select Microsoft Excel as the data source.
-Browse to the location of your Excel file.
-Select the Excel version and make sure the First row has column names option is checked if your Excel file includes headers.
 
4. Choose a Destination:
-Select SQL Server Native Client as the destination.
-Specify the SQL Server instance and database where you want to import the data.
 
5. Specify Table Copy or Query:
-Choose to copy data from one or more tables or to write a query to specify the data to transfer.
-For simple imports, copying from tables is usually sufficient.

6. Select Source Tables and Views:
-Select the specific Excel sheets or ranges you want to import.

7. Configure Column Mappings (if needed):
-Review and modify column mappings to ensure data types and destinations are correct.

8. Run the Import:
-Execute the import and monitor the progress.
-After completion, verify that the data has been imported correctly into the target SQL Server table.
