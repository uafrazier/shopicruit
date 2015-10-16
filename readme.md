A simple web page to demonstrate how to use JavaScript to filter, sum and display JSON data from a remote server.

In this example, the data is a product list from a Shopify store.  The data is in JSON format and can be accessed at http://shopicruit.myshopify.com/products.json

The script uses the [JSONP](https://en.wikipedia.org/wiki/JSONP) technique to get the JSON data from the remote server.  We don't want to display all the data that is returned so we'll filter the data by type and only display certain information from the filtered data.  Finally, the prices of all the items displayed are summed to get a total price for display.
