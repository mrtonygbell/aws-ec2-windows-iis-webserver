# aws-ec2-windows-iis-webserver
Deploying a Windows EC2 instance on AWS and installing IIS to host a web server.
## Project Overview
This project demonstrates how to deploy a Windows server in AWS and configure a web server using IIS. 
The server is hosted on an EC2 instance and accessed remotely using Remote Desktop Protocol (RDP).

## Technologies Used
- AWS EC2
- Windows Server
- IIS Web Server
- Remote Desktop Protocol (RDP)

## Architecture
Internet
   |
Security Group
   |
EC2 Windows Server
   |
IIS Web Server
   |
Hosted Web Page

## Deployment Steps

1. Launched a Windows EC2 instance in AWS
2. Created and downloaded a key pair for secure access
3. Configured a security group allowing RDP access on port 3389
4. Connected to the server using Remote Desktop
5. Installed IIS using command line tools
6. Verified the web server installation by loading the default webpage

## Security Notes
For lab purposes, RDP access was allowed from anywhere (0.0.0.0/0). 
In a production environment this should be restricted to a specific IP address, VPN connection, or bastion host.

## Screenshots
(Add screenshots showing the EC2 instance, security group configuration, RDP connection, and IIS webpage.)
