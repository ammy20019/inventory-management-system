# No_SQL_project

### Create dbconnect.php file with following details
<?php 
require_once __DIR__ . '/mongo/vendor/autoload.php';
 $con = new MongoDB\Client("mongodb://localhost:27017");
 ?>

We are doing a Sales mannagment project using php and MongoDB for our NoSql course project.

Note : If you want to use our project then you have to delete mongo folder and install it again using composer and mongo_php dll. Later, you have to extend to your php files.
