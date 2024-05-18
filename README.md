ABOUT THE BILL APP:

This app is basically created for a shopkeeper which can generate bills on the basis of the items purchased by the customer. The shopkeeper can see the list of products available, can add, update or delete a product. Shopkeeper can see the list of customers and can perform all the CRUD operations related to the customer. He/She can find the customer based on GST Number or Invoice Number of the customer and can also delete a bill for a particular customer. 

For an example if a new customer comes then the shopkeeper will go to the Add Customer tab enter the details of the customer and then add items. After this he/she can save the customer data which will be persisted in mysql database. Once the customer is saved it's bill will be created in a html file in the unpaid directory. The shopkeeper can also update the payment status of the customer by clicking on view button and then clicking on the update payment status in the view bills page.

NOTE: Your 3000, 8083, 3306 ports should be free in order to run this app

In order to run this app you need to perform only six steps:

Step 1: Install docker in your system

Step 2: Clone the Repository

Step 3: Open terminal and run the command => (docker-compose up) where docker-compose.yml is present

Step 4: Access the app using the url => http://localhost:3000/

Step 5: Start adding the products in the Add Product tab

Step 6: Once the list of products is created by the user/shopkeeper he/she can add customer and start generating bills for them.
