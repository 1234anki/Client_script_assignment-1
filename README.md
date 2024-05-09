# Client_script_assignment-1

Overview
This tool allows users to export customer data to a CSV (Comma Separated Values) file format. It includes the customer's name, email address, mobile number, and associated address details.

## Backend Logic
The backend logic is implemented using Python with the Frappe framework. It fetches customer and address data from the database and prepares it for export to a CSV file.

### Export Customers List Function
The `export_customers_list` function queries the database to fetch customer data along with associated address details. It returns the data as a list of lists.

## Frontend Logic
The frontend logic is implemented using JavaScript with Frappe framework. It adds an "Export" button to the Customer List View and triggers the export functionality when clicked.

### Export Button
The export button is added to the Customer List View. When clicked, it calls the backend function `export_customers_list` to fetch customer data and prepares it for export.


Usage
1. Open your web browser and navigate to the Frappe application.
2. Go to the Customer List View.
3. Click on the "Export" button to export customer data to a CSV file.


