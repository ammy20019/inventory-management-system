# No_SQL_project

### Create dbconnect.php file with following code:

require_once __DIR__ . '/mongo/vendor/autoload.php';<br>
 $con = new MongoDB\Client("mongodb://localhost:27017");

### Create branchdbconnect.php file inside the branch folder with following code:

require_once __DIR__ . '/mongo/vendor/autoload.php';
 $con = new MongoDB\Client("mongodb://localhost:27017");

### Developed by 💻 <br>
✔<a href="https://github.com/rushik-010801"> Rushik Kumar Avula</a><br>
✔<a href="https://github.com/ammy20019"> Amit Kumar Sahu</a>

We are doing a Sales mannagment project using php and MongoDB for our NoSql course project.

Note : If you want to use our project then you have to delete mongo folder and install it again using composer and mongo_php dll. Later, you have to extend to your php files.
