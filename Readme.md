<h3>General Instructions</h3>

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

<ul>
<li>Invoice Number</li>
<li>Date</li>
<li>Customer Name (FK to table Customers)</li>
<li>Invoice Amount (Sum of Quantity * UnitPrice in table InvoiceDetails)</li>
</ul>

Also the datagrid will have a custom column with "Details" button. When the user clicks on "Detail" a modal bootstrap window will appear showing the next information:

<ul>
<li>Invoice Number</li>
<li>Date</li>
<li>Customer Name</li>
<li>Notes</li>
</ul>

Below that text fields, please add another datagrid to show the invoice detail information with the next columns:

<ul>
<li>Product Id</li>
<li>Product Name (FK to Products table)</li>
<li>Quantity</li>
<li>UnitPrice</li>
<li>Total (Quantiy * UnitPrice)</li>
</ul>

Use the bootstrap modal object to create the modal window:

http://getbootstrap.com/

http://getbootstrap.com/javascript/#modals

Also feel free to usa the bootstrap framework to format your textboxes, labels, list, etc


<h3>Database Creation</h3>

In order to create the database, please run the file CreateDatabase.sql on your local instance of SQL Server. The script is located in :

ExamSSMDataLayer\Database Scripts


<h3>Final Considerations</h3>

Please send your finished project in a zip file to the email of the person who contacted you. 

Thanks and Good Luck!!!