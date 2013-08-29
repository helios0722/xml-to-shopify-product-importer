XML -\> Shopify Product Importer
================================

Export products from BigCommerce, import to Shopify. Forget the app store!

Getting Started
---------------

To get started, you will need to export your BigCommerce data in XML format.
Then, you will run this parser, which will create a CSV file that respects
Shopify's headers. Finally, you will import this into Shopify.

### First Steps (Export from BigCommerce)

First, you need to create a template to export your product data.

1.  To get started, log in to your BigCommerce dashboard.

2.  Click on the 'Advanced Settings' menu, then select the 'Exports Template'
    panel.

3.  Click on the button to create a new template.

4.  On the Template Details page, select *only* the `Enable Products Exporting?`
    checkbox.

5.  Switch to the Products tab, and click the checkbox in the top left corner
    (in the header row). This will select everything.

6.  Save your template.

Next, you'll want to export your products.

1.  Go back to the BigCommerce dashboard.

2.  Click on the 'Products' menu, and select the 'Export' panel.

3.  Select the template you created.

4.  Choose `Export to an XML File (Advanced)`.

5.  Click 'Continue', and download the file.

### Installing

Copy the XML file that you downloaded from BigCommerce to the directory.

Use the config.php.example file to point to your XML file. Rename it
`config.php`.

### Running the Application

Load the index.php file in your browser. It will output the CSV file to the
screen, as well as create a `shopify.csv` file in the local directory.

### Final Steps: Importing to Shopify

In your Shopify dashboard, click on the Products tab, select import, and choose
your file.

License
-------

This project is licensed under the MIT License - see the
[LICENSE.md](LICENSE.md) file for details

 
-
