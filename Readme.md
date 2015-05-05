This is a empty project template to evaluate the skills of the .net developers in the next areas:

<ul>
<li>ASP.Net MVC</li>
<li>Entity Framework</li>
<li>Javascript</li>
<li>AJAX</li>
<li>JQuery</li>
</ul>

The project contains an empty view, your task is to add a datagrid using :

http://www.jquery-bootgrid.com/


The datagrid will show the next columns:

Invoice Number
Date
Customer Name (FK to table Customers)
Invoice Amount (Sum of Quantity * UnitPrice in table InvoiceDetails)

Also the datagrid will have a custom column with "Details" button. When the user clicks on "Detail" a modal bootstrap window will appear showing the next information:

Invoice Number
Date
Customer Name
Notes

Below that text fields, please add another datagrid to show the invoice detail information with the next columns:

Product Id
Product Name (FK to Products table)
Quantity
UnitPrice
Total (Quantiy * UnitPrice)

Use the bootstrap modal object to create the modal window:

http://getbootstrap.com/
http://getbootstrap.com/javascript/#modals

Also feel free to usa the bootstrap framework to format your textboxes, labels, list, etc


Database Creation

In order to create the database, please run the file CreateDatabase.sql on your local instance of SQL Server. The script is located in :

ExamSSMDataLayer\Database Scripts