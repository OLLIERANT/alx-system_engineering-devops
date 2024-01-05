<b>0x0F. Load balancer</b>
<b>Concepts</b>
For this project, we expect you to look at these concepts:
	Load balancer
	Web stack debugging

Background Context
You have been given 2 additional servers:
	gc-[STUDENT_ID]-web-02-XXXXXXXXXX
	gc-[STUDENT_ID]-lb-01-XXXXXXXXXX

Let’s improve our web stack so that there is redundancy for our web servers. This will allow us to be able to accept more traffic by doubling the number of web servers, and to make our infrastructure more reliable. If one web server fails, we will still have a second one to handle requests.
For this project, you will need to write Bash scripts to automate your work. All scripts must be designed to configure a brand new Ubuntu server to match the task requirements.

TASK 0: Write 0-custom_http_response_header so that it configures a brand new Ubuntu machine to the requirements asked in this task
	Requirements:
		Configure Nginx so that its HTTP response contains a custom header (on web-01 and web-02)
		The name of the custom HTTP header must be X-Served-By
		The value of the custom HTTP header must be the hostname of the server Nginx is running on
TASK 1: Install and configure HAproxy on your lb-01 server.
	Requirements:
		Configure HAproxy so that it send traffic to web-01 and web-02
		Distribute requests using a roundrobin algorithm
		Make sure that HAproxy can be managed via an init script
		Make sure that your servers are configured with the right hostnames: [STUDENT_ID]-web-01 and [STUDENT_ID]-web-02. If not, follow this tutorial.
		For your answer file, write a Bash script that configures a new Ubuntu machine to respect above requirements
TASK 2: Just as in task #0, we’d like you to automate the task of creating a custom HTTP header response, but with Puppet.
	The name of the custom HTTP header must be X-Served-By
	The value of the custom HTTP header must be the hostname of the server Nginx is running on
	Write 2-puppet_custom_http_response_header.pp so that it configures a brand new Ubuntu machine to the requirements asked in this task



