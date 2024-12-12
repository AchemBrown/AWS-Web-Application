# AWS EC2 Instance with Apache Web Server for Smartshop
This project documents the processs of launching an EC2 instance with Apache Web Server for Smartshop.
## Lauching an EC2 Instance
Logged in to the AWS Management Console and navigated to the EC2 instance and launched an instance.
![EC2 instance creation](<Screenshot 2024-12-11 at 8.31.47 PM.png>)
![EC2 Instance overview](<Screenshot 2024-12-11 at 8.35.17 PM.png>)
### Security Group
Created Security Group to control inbound and outbound traffic. Added and inbound rule to allow HTTP traffic from anywhere and outbound rule to allow all traffic 
![security group](<Screenshot 2024-12-11 at 1.53.26 PM.png>)
### Apache Web Server
Connected to the running EC2 instance using SSH.
Updated the system by using sudo yum update -y
Installed Apache and verified if its works.
![Apache Server](<../../../Desktop/Screenshot 2024-12-12 at 2.52.09 PM.png>)