# AWS EC2 Nginx Lab

## AWS Services Used

- EC2
- Security Groups
- VPC

---

## Steps

### Launch EC2

Created Ubuntu EC2 instance.

Allowed

- Port 22
- Port 80

Connected using SSH.

---

### Update Packages

sudo apt update
sudo apt upgrade -y
sudo apt install nginx -y
sudo systemctl status nginx
sudo systemctl restart nginx

HTML Page is Created
http://Public-IP
