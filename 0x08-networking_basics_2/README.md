0x08. Networking basics #1

Learning Objectives:
	1. What is localhost/127.0.0.1
	2. What is 0.0.0.0
	3. What is /etc/hosts
	4. How to display your machine’s active network interfaces.

File 0. 0-change_your_home_IP
Write a Bash script that configures an Ubuntu server with the below requirements.

Requirements:

	1. localhost resolves to 127.0.0.2
	2. facebook.com resolves to 8.8.8.8.

File 1. 1-show_attached_IPs
Write a Bash script that displays all active IPv4 IPs on the machine it’s executed on.

File 2. 100-port_listening_on_localhost
Write a Bash script that listens on port 98 on localhost.

	Terminal 0 Starting my script.
	Terminal 1 Connecting to localhost on port 98 using telnet and typing some text.
	Terminal 0 Receiving the text on the other side.
