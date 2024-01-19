0x0B-ssh
Along with this project, you have been attributed an Ubuntu server, living in a datacenter far far away. Like level 2 of the application process, you will connect using ssh. But contrary to level 2, you will not connect using a password but an RSA key. We’ve configured your server with the public key you created in the first task of a previous project shared in your intranet profile.

You can access your server information in the my servers section of the intranet, each line with contains the IP and username you should use to connect via ssh.

Note: Your server is configured with an Ubuntu 20.04 LTS environment.
Learning Objectives:
	What is a server
	Where servers usually live
	What is SSH
	How to create an SSH RSA key pair
	How to connect to a remote host using an SSH RSA key pair
	The advantage of using #!/usr/bin/env bash instead of /bin/bash

File 0-use_a_private_key: Write a Bash script that uses ssh to connect to your server using the private key ~/.ssh/school with the user ubuntu.

File 1-create_ssh_key_pair: Write a Bash script that creates an RSA key pair.

File: 2-ssh_config: Share your SSH client configuration in your answer file.
Task 3: Add public key provided to your web-01 server.
