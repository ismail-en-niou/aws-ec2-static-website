# AWS EC2 Static Website Deployment

## Project Overview
This project demonstrates how to deploy a static website using an AWS EC2 Ubuntu server and Nginx web server.

## Live Website URL
http://YOUR_EC2_PUBLIC_IP

## Steps Followed

### 1. Created AWS EC2 Instance
- Ubuntu Server AMI
- t2.micro (Free Tier)
- Security Group opened ports 22 and 80

### 2. Connected via SSH
```bash
ssh -i roadmap.pem ubuntu@YOUR_EC2_PUBLIC_IP
3. Installed Nginx
sudo apt update -y
sudo apt install nginx -y
4. Deployed Website

Created a simple HTML file in:

/var/www/html/index.html
5. Access Website

Opened in browser:

http://YOUR_EC2_PUBLIC_IP
Technologies Used
AWS EC2
Ubuntu Server
Nginx
HTML
Author

Ismail En-niou

```
https://roadmap.sh/projects/ec2-instance
