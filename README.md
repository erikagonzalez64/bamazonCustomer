# BamazonCustomer
# Overview
  Bamazon is an Amazon-like storefront which uses MySQL and node.js. The app will take in orders from customers and will update the amount of items left from the store's inventory.
# Bamazon Customer View
* Running bamazonCustomer.js will display all of the items available for sale. It will include the ids, names, prices of products for sale and the stock quantity.
*The app will then promt users with two messages.
  1. The first message will ask for the ID of the product that they would like to buy.
  2. The second message will ask how many units of the product you would like to buy.
* Once the customer has placed the order, the application will check if they store has that many product items to meet the customer's request. If not, the app will log the phrase Insufficient quantity, and prevent the order from going through. The app requires 'npm inquirer' and 'npm mysql'.

# Screenshots of my work :)
1. The app first displays all items available for sale in the bamazon inventory.


[I'm an inline-style link](https://github.com/erikagonzalez64/bamazonCustomer/blob/master/images/tablescreenshot.png)

2. The app then prompts users with two messages, to place an order. The cost of the purchase is also displayed.

---insert picture of both questions answered and the data it gives you back--------


3. The app then updates the database to reflect the remaining inventory.


-----insert the pic of work updated -------------
