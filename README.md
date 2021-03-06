# Mysql-Amazon
Amazon inventory!


Mysql-Amazon is a CLI app that works on three levels:

* A MySQL database called "bamazon" that has a table called "products" ![Image of products table in bamazon]
(https://github.com/Abdeluswho/Mysql-Amazon/blob/master/Images/Bamazon%20Database%20(MySQL).png)

* A **Customer** view, accessed by the terminal command **node bamazonCustomer.js**
- this shows a customer view of a failure to purchase due to an insufficient supply ![insufficient supply]
   (https://github.com/Abdeluswho/Mysql-Amazon/blob/master/Images/Customer%20View%20(failure%20to%20purchase).png)
- and a customer view of a successful purchase ![successful purchase](https://github.com/Abdeluswho/Mysql-Amazon/blob/master/Images/Customer%20View%20(successful%20purchase).png)

* A **Manager** view, accessed by the terminal command **node bamazonManager.js**
- this shows a managerial view with four different options and operations ![four different options and operations](https://github.com/Abdeluswho/Mysql-Amazon/blob/master/Images/Manager%20View%201%20(default).png)
- the first option shows all available inventory in the database ![all available inventory in the database](https://github.com/Abdeluswho/Mysql-Amazon/blob/master/Images/Manager%20View%202%20(all%20inventory).png)
- the second option displays low inventory, more specifically all product items below 100 units ![all product items below 100 units](https://github.com/Abdeluswho/Mysql-Amazon/blob/master/Images/Manager%20View%203%20(low%20inventory).png)
- the third managerial option allows a manager to add more units to a low inventory product ![add more units to a low inventory product](https://github.com/Abdeluswho/Mysql-Amazon/blob/master/Images/Manager%20View%204%20(add%20to%20inventory).png)
- the last managerial option allows the manager to add a new product, with the CLI prompting the manager specific questions about the product ![CLI prompting the manager specific questions about the product](https://github.com/Abdeluswho/Mysql-Amazon/blob/master/Images/Manager%20View%205%20(add%20new%20product).png)


