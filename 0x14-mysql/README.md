0x14. MySQL

Concepts & Resources
For this project, we expect you to look at these concepts:
	Database administration
	Web stack debugging
	[How to] Install mysql 5.7

TASKS:
(0). Get MySQL installed on both your web-01 and web-02 servers.
(1). Create a MySQL user named holberton_user on both web-01 and web-02 with the host name set to localhost and the password projectcorrection280hbtn. This will allow us to access the replication status on both servers.
(2). In order for you to set up replication, you’ll need to have a database with at least one table and one row in your primary MySQL server (web-01) to replicate from.
(3). Before you get started with your primary-replica synchronization, you need one more thing in place. On your primary MySQL server (web-01), create a new user for the replica server.
(4). Setup a Primary-Replica infrastructure using MySQL
(5). Write a Bash script that generates a MySQL dump and creates a compressed archive out of it.
