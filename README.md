# Inventory Management System 🏢
#### No_SQL_project

### Abstract 💾
This report is based on the project we have done, which is called Inventory Management Software. This is developed mostly based on the trending NoSQL solution MongoDB. The main use of the above mentioned software is for the retailers who want to manage their product stocks among their various branches. The project is with a well understandable user interface with well formed security. The total code for this project can be found here. Since the NoSQL solution is MongoDB we can say that our software is able to manage heavy data efficiently. Presently for the demo purpose we have initiated the software with 1k rows of data. With our software the stock manager can check for the products in the company's godown as well as insert, delete, update the products. We also have employed a chat feature for the go down manager and branch manager. Branch office has a separate module which is used for checking the product data present in the branch. This module also has the ability to insert, update the stock present in the branch.

### Technologies Used 💾

|Front End | Bootstrap4 | 

| Back End  | PHP - Composer (PHP v7) |

| Database | MongoDB Atlas |

| Server | Heroku |


### Create dbconnect.php file with following code:

require_once __DIR__ . '/mongo/vendor/autoload.php';<br>
 $con = new MongoDB\Client("mongodb://localhost:27017");

### Create branchdbconnect.php file inside the branch folder with following code:

require_once __DIR__ . '/mongo/vendor/autoload.php';<br>
 $con = new MongoDB\Client("mongodb://localhost:27017");

### Cheers to our team 🥂<br>
✔<a href="https://github.com/rushik-010801"> Rushik Kumar Avula 💻</a><br>
✔<a href="https://github.com/ammy20019"> Amit Kumar Sahu 💻</a>

### Working Methodology 💾
The project is completely based on software with two sections, front-end and back-end. The front-end consists of a Bootstrap4 file. It has been hosted on Heroku (powered by Salesforce). The back-end is built using PHP-Composer. With a database as MongoDB atlas.

This application is used to show the stock details. It gives the details with search options by Category, by Product ID, or by Product Name. The details components are described below:

Admin Login page: As application starts the login page appears. Admin login is determined by the username and password that has all the authority to send message, search, add, update and delete the stock of the organization as per the requirement.

Create Branch: Admin can create a branch if he/she needs to extend or manage their product and shops easily. He can create the account of the branch along with Branch Name, Branch ID, Password and Address. Later he can share credentials to the Branch Manager to handover.

Branch Login page: This page is exclusively for branch manager login. The branch manager can send messages to other branches or the admin about the stocks and update them about his.her branch status, also the branch manager can search or insert products to the database.  

### Snaps 
#### Home Page
![Test Image 5](https://github.com/ammy20019/inventory-management-system/blob/master/Snaps/index.png)

#### Dahboard Admin
![Test Image 5](https://github.com/ammy20019/inventory-management-system/blob/master/Snaps/s1.png)

### Stocks view
![Test Image 5](https://github.com/ammy20019/inventory-management-system/blob/master/Snaps/s2.png)

### Search
![Test Image 5](https://github.com/ammy20019/inventory-management-system/blob/master/Snaps/s3.png)

### Insert Product
![Test Image 5](https://github.com/ammy20019/inventory-management-system/blob/master/Snaps/s4.png)

### Insert Product with new category
![Test Image 5](https://github.com/ammy20019/inventory-management-system/blob/master/Snaps/s5.png)

### Update Product
![Test Image 5](https://github.com/ammy20019/inventory-management-system/blob/master/Snaps/s6.png)

### Delete
![Test Image 5](https://github.com/ammy20019/inventory-management-system/blob/master/Snaps/s9.png)

### Analytcs
![Test Image 5](https://github.com/ammy20019/inventory-management-system/blob/master/Snaps/s7.png)

### Add New Branch for the inventory
![Test Image 5](https://github.com/ammy20019/inventory-management-system/blob/master/Snaps/s8.png)

### Branch Manager Login Dashboard
![Test Image 5](https://github.com/ammy20019/inventory-management-system/blob/master/Snaps/S10.png)


Note : If you want to use our project then you have to delete mongo folder and install it again using composer and mongo_php dll. Later, you have to extend to your php files.
