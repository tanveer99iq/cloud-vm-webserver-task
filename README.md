# Deploy a Virtual Machine & Install Web Server

## Cloud Platform
AWS EC2 Ubuntu Instance

## Public VM URL
http://16.171.34.204

## Steps Performed
1. Created Ubuntu EC2 instance
2. Allowed HTTP traffic (Port 80)
3. Installed Apache Web Server
4. Created custom webpage
5. Accessed website using public IP

## Commands Used

```bash
sudo apt update
sudo apt install apache2
sudo systemctl start apache2
sudo systemctl enable apache2
sudo nano /var/www/html/index.html
```

## Output
Hello from Cloud VM
