# Power-Query-Project---Gmail_To_Excel_files
Automated Excel data consolidation from Gmail using Google Apps Script and Power Query. Fetches Excel attachments, converts Base64 to binary, reads multiple workbooks, and appends data into a single report with one-click refresh. Demonstrates ETL, API integration, and Excel automation..

# Append Excel Files from Gmail Using Google Apps Script & Power Query

This project demonstrates an automated solution for extracting Excel file attachments from Gmail and consolidating their data into a single Excel report using Google Apps Script and Microsoft Power Query. It eliminates the need for manually downloading email attachments and copying data from multiple files, making the reporting process faster, more accurate, and highly efficient.

The solution uses a Google Apps Script deployed as a Web App to access the user's Gmail inbox and retrieve Excel attachments from recent emails. The script extracts important email metadata such as the sender, subject, date, attachment name, and converts the attachment into a Base64 string. Power Query then connects to the Web App's JSON response, decodes the Base64 content into binary format, and dynamically reads each Excel workbook using the Excel.Workbook() function.

After loading the workbooks, Power Query automatically transforms, cleans, and appends data from all attachments into a single consolidated table. Whenever new Excel files are received in Gmail, users simply need to refresh the Power Query connection to update the report without modifying any queries or downloading files manually.

This project showcases practical ETL (Extract, Transform, Load) techniques and demonstrates how APIs, automation, and Power Query can work together to streamline business reporting workflows. It is particularly useful for organizations that receive recurring reports, invoices, sales data, financial statements, or operational data through email.

# Key Features
Fetch Excel attachments directly from Gmail.
Google Apps Script Web App integration.
API-based data retrieval.
Base64 to Binary conversion in Power Query.
Automatic reading of multiple Excel workbooks.
Data transformation and consolidation.
One-click refresh for updated reports.
Fully automated reporting workflow.
Technologies Used
Microsoft Excel
Power Query (M Language)
Google Apps Script
Gmail Services
JSON API
ETL Concepts


This project demonstrates skills in Data Analytics, Power Query, API Integration, Excel Automation, Data Transformation, Business Intelligence, and Workflow Automation. It serves as a practical example of building real-world automation solutions that reduce manual effort, improve productivity, and create scalable reporting processes for business operations. It is an excellent portfolio project for aspiring Data Analysts, Business Intelligence Developers, and Excel Automation Specialists.
