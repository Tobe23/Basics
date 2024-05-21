# Web Stack Implementation in AWS

## Lamp Stack

There are different stacks of technology that make different solutions possible. These stacks of technology are regarded as WEB STACK, examples of Web Stack are LAMP, LEMP, MEAN, and MERN stacks.

LAMP stands for Linux Apache MySQL PHP. This means that Linux (ubuntu) OS is required, also that Apache, MySQL, and PHP should be installed.

### Installing Apache

The package manager for ubuntu is apt.

sudo apt update command is used to update list of packages in the package manager

![alt text](<Images/Screenshot 2024-05-21 140119.png>)

sudo apt install apache2 is for installing apache

![alt text](<Images/Screenshot 2024-05-21 140441.png>)

sudo systemctl status apache2 to verify that apache2 is running as a service in the OS.

![alt text](<Images/Screenshot 2024-05-21 140913.png>)

curl command is used to request Apache HTTP server to run on port 80

curl http://localhost:80 or curl http://51.20.77.196:80 

![alt text](<Images/Screenshot 2024-05-21 143843.png>)

### Installing MySQL

Now that the web server is up and running, a Database Management System needs to be installed to be able to store and manage data for the site in a relational database. MySQL is a apopular relational database management system used in PHP environment.

sudo apt install mysql-server command is for installing for mysql

![alt text](<Images/Screenshot 2024-05-21 144934.png>)

Log into MySQL server by running sudo mysql

![alt text](<Images/Screenshot 2024-05-21 145318.png>)


sudo mysql_secure_installation command is used to run a security script that comes pre-installed with MySQL.

![alt text](<Images/Screenshot 2024-05-21 162356.png>)

Run sudo mysql -p to log into mysql console

![alt text](<Images/Screenshot 2024-05-21 163043.png>)

### Installing PHP

Run sudo apt install php libapache2-mod-php php-mysql to install PHP, php-mysql (a PHP module that allows PHP to communicate MySQL-based database) and lipapache2-mod-php to enable apache to handle PHP files

![alt text](<Images/Screenshot 2024-05-21 164225.png>)

![alt text](<Images/Screenshot 2024-05-21 173029.png>)

![alt text](<Images/Screenshot 2024-05-21 173159.png>)

![alt text](<Images/Screenshot 2024-05-21 173504.png>)
