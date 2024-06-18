# Implement a Client Server Architecture using MYSQL Database Management System (DBMS)

1. Create and configure two Linux-based servers (EC2 instances in AWS)

Server A name - `mysql server`
Server B name - `mysql client`

2. On MySQL server install MySQL Severs Software

Because it is ubuntu we use the following command
sudo apt update and sudo apt install mysql-server

![alt text](<Images/Screenshot 2024-06-16 064131.png>)

![alt text](<Images/Screenshot 2024-06-16 064320.png>)

Once the installation is complete, the MySQL server should be started automatically. Quickly check its current status via systemd - sudo service mysql status

![alt text](<Images/Screenshot 2024-06-16 064735.png>)

3. On mysql client install MySQL Client software.
This is also an ubuntu linux OS so we update and install as usual with apt update and apt install mysql-client

![alt text](<Images/Screenshot 2024-06-16 065735.png>)

Quickly run mysql --version to confirm installation.

![alt text](<Images/Screenshot 2024-06-16 070028.png>)

On mysql server, use nano editor to configure the bind-address to 0.0.0.0 as shown below.

![alt text](<Images/Screenshot 2024-06-16 084001.png>)

4. By default, both EC2 virtual servers are located in the same local virtual network, so they can communicate to each other using local IP addresses. Use MySQL server's local IP address to connect from MySQL client. MySQL server uses TCP port 3306 by default, so it has to be open enabled in inbound rules in MySQL server security groups. For extra security, do not allow all IP addresses to reach your MySQL server - allow access only to the specific local IP address of your msql client.

![alt text](<Images/Screenshot 2024-06-16 215849.png>)

Since mysql database does not allow root connection, a user has to be created as shown below.

![alt text](<Images/Screenshot 2024-06-16 204917.png>)

Now connect using "mysql -u tobe -p -h private_ip_of_server"

![alt text](<Images/Screenshot 2024-06-16 220845.png>)