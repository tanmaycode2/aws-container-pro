## Create two EC2 instances and put the user data as below:
#!/bin/bash
# Use this for your user data (Script from top to bottom)
# install https (Linux 2 version)
yum update -y
yum install -y httpd
systemctl start httpd
systemctl enable httpd
# echo command in linux is used to display line of text/string that are passed as an argument 
echo "<h1>Hello World from $(hostname -f)</h1>" > /var/www/html/index.html

This will install the webserer and displays the availabilty zone of our instances.
