# HOSTING_CUSTOM_WEBSITE
Task :- Created a custom website and started the web server:

This project involved hosting a website on AWS using MobaXterm, and it has been an incredible learning experience.
## Project Highlights:
- 1️. Logged into the AWS Console to get started.
- 2️.Created and launched an EC2 instance.
- 3️. Configured the security groups:
Port 22 (SSH) for admin access only.
Port 80 for normal web traffic.
- 4️. Connected to the EC2 machine using MobaXterm.
- 5️. Installed and configured the HTTPD web server to host the website:
sudo su 
yum update -y 
yum install httpd -y 
cd /var/www/html 
Created a custom website and started the web server:
service httpd start 
- 6️. Successfully accessed the website through the public IP or DNS of the EC2 instance.
