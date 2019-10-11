# BamazonCustomer
# Overview
  Bamazon is an Amazon-like storefront which uses MySQL and node.js. The app will take in orders from customers and will update the amount of items left from the store's inventory.
# Instructions
  The database is called 'bamazon_DB' with a Table called 'products'. Schema is attached in the schema.js file.

Running the Node application called 'bamazonCustomer.js' application will first display all of the items available for sale. Include the ids, names, prices and quantities of products for sale.

Bamazon then prompts users with two messages: * The first ask them the ID of the product they would like to buy. * The second message should ask how many units of the product they would like to buy.

Once an order has been placed the application checks to see if the store has enough of the product to meet the user's request. If not, the app log the insufficient stock and recursively ask the item ID again.

However, if the store does have enough of the product, It will fulfill the user’s order showing the total price and quantity of the order as well as updating the SQL database to reflect the new quantity.

# Screenshots of my work :)
1. The app first displays all items available for sale in the bamazon inventory.


[Link to my data/table screenshot](https://github.com/erikagonzalez64/bamazonCustomer/blob/master/images/tablescreenshot.png)

2. The app then prompts users with two messages, to place an order. The cost of the purchase is also displayed.

[Link to questions answered screenshot](https://github.com/erikagonzalez64/bamazonCustomer/blob/master/images/questionsanswered.png)

3. The app then updates the database to reflect the remaining inventory.


[Link to my table being updated screenshot](https://github.com/erikagonzalez64/bamazonCustomer/blob/master/images/updatedtable.png)
