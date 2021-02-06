# Rest-Api-Auth-PHP-JWT
## 🚀 Get Started

1. **SETUP THE DATABASE.**

   ```sh
   # Open your PhpMyAdmin localhost/phpmyadmin
   1 - Create a database called "phprestapi"
   2-  Create a table called "users"
       SQL Commant "CREATE TABLE users(
                        id int(11) PRIMARY KEY AUTO_INCREMENT NOT NULL,
                        firstname varchar(128) NOT NULL,
                        lastname varchar(128) NOT NULL,
                        email varchar(128) NOT NULL,
                        passwrd varchar(2048) NOT NULL
                        );" 

   3-  Create a table called "products"
       SQL Commant "CREATE TABLE products(
                        id int(11) PRIMARY KEY AUTO_INCREMENT NOT NULL,
                        urunadi varchar(128) NOT NULL,
                        urungorseli varchar(128) NOT NULL,
                        urunfiyati varchar(128) NOT NULL,
                        );" 
   4-  Create a table called "payments"
       SQL Commant "CREATE TABLE payments(
                        id int(11) PRIMARY KEY AUTO_INCREMENT NOT NULL,
                        kartno varchar(128) NOT NULL,
                        kartsahibi varchar(128) NOT NULL,
                        sonkultarihi varchar(128) NOT NULL,
                        cvv varchar(128) NOT NULL,
                        );" 
   ```
2. **SETUP YOUR DATABASE CONNECTION FİLE**
   
   ```sh
   # specify your own database credentials
   
   1- Open database.php folder and fill up like this.
        
        private $host = "localhost";
        private $db_name = "phprestapi";
        private $username = "root";
        private $password = "";
        public $conn;
   ```
   
3. **YOU ARE READY! 🚀🚀🚀**
```sh
   # Enter the following as the request URL
   http://localhost/rest-api-auth/
   ```

