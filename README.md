# Web Server Setup on Ubuntu

This project demonstrates how to set up a basic web server on Ubuntu Linux using **Apache**.  
The goal was to learn Linux fundamentals, practice server management, and understand how web hosting works locally before moving to the cloud (AWS).

# Steps Performed

1. **Updated System Packages**
   ```bash
   sudo apt update
   sudo apt upgrade -y
2. **Installed Apache Web Server**
   ```bash
   sudo apt install apache2 -y
3. **Started And Enabled Apache Web Server**
   ```bash
   sudo systemctl start apache2
   sudo systemctl enable apache2
4. **Opened HTML Main Page**
   ```bash
   sudo nano /var/www/html/index.html
5. **Created A Custom HTML Page**
   ```bash
   <html>
   <h1>Hello, my name is Ashwin and this is my first Linux Project.</h1>
   <p>This page is served from (ashwin-linux)</p>
   </html>
 6. **Verified The Web Page**
    Opened the browser and typed "file:///home/ashwin/Ashwin1" because the file name is 'Ashwin1' and the path for this file is '/home/ashwin/Ashwin1'.
