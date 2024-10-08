# Deploying a Web Application on AWS

- **NAME**: NETHRA V
- **COMPANY**: CODTECH IT SOLUTIONS
- **INTERN ID**: CT08DS5285
- **DOMAIN**: CLOUD COMPUTING
- **BATCH DURATION**: 23 JULY TO 23 AUGUST 2024
- **MENTOR**: MUZAMMIL AHMED

## Project Description

This project involves deploying a web application to an Amazon Linux 2 instance using Apache HTTP Server. The web application consists of HTML, CSS, JavaScript, and image files. The goal is to configure the Apache HTTP Server to serve these files, making the web application accessible over the internet.

## Technologies Involved

- **Amazon Linux 2**: The operating system used for the EC2 instance. It provides a stable, secure, and high-performance execution environment for applications.
- **Apache HTTP Server**: A widely-used web server software that serves web pages over HTTP. It handles requests from clients and delivers the web application files.
- **EC2 (Elastic Compute Cloud)**: AWS service that provides scalable virtual servers in the cloud to host web applications and other services.
- **HTML/CSS/JavaScript**: Core technologies used to build and style the web application. HTML structures the content, CSS styles it, and JavaScript adds interactivity.
  
## Detailed Procedure

### Updating the System

Ensure that your Amazon Linux 2 instance is running the latest software and security updates. This step prepares the environment for installing new software.

### Installing the Apache HTTP Server

Install Apache HTTP Server (httpd) to handle HTTP requests and serve your web application to users.

### Verifying the Apache Installation

Check the status of the Apache service to confirm that it is installed correctly. The service might be inactive initially, but it will be addressed in subsequent steps.

### Preparing the Web Application Files

Download or clone the web application files from a repository or ZIP archive. These files include `index.html`, `styles.css`, `script.js`, and image files.

### Deploying the Web Application

Move the web application files to the `/var/www/html/` directory. This directory is used by Apache HTTP Server to serve web content.

### Configuring and Starting the Apache HTTP Server

Enable Apache HTTP Server to start on boot and start the service. This ensures that the server is running and serving your web application.

### Verifying the Deployment

Access the public IP address of your EC2 instance in a web browser to confirm that the web application is being served correctly.

The application is now accessible via the public IP address of your EC2 instance, demonstrating a successful deployment on AWS.

## Linux Commands Used

### Switching to the root user

sudo su -

### Updating the system

yum update -y

### Installing the Apache HTTP Server

yum install -y httpd

### Checking the status of the Apache HTTP Server

systemctl status httpd

### Creating a directory named 'tech'

mkdir tech

### Navigating to the tech directory

cd tech

### Downloading the GitHub repository

wget https://github.com/Nethra2004/Nethra-V_Portfolio.git

### Downloading the ZIP archive of the repository

wget https://github.com/Nethra2004/Nethra-V_Portfolio/archive/refs/heads/main.zip

### Listing the files in the tech directory

ls -lrt

### Unzipping the downloaded ZIP archive

unzip main.zip

### Navigating to the unzipped directory

cd Nethra-V_Portfolio-main

### Moving all the files to the Apache web directory

mv * /var/www/html/

### Navigating to the Apache web directory

cd /var/www/html

### Listing files in the Apache web directory

ls -lrt

### Enabling the Apache HTTP Server to start on boot

systemctl enable httpd

### Starting the Apache HTTP Server

systemctl start httpd


## Launching an EC2 Instance

![Screenshot (633)](https://github.com/user-attachments/assets/53a6bf0b-c704-421b-8d4e-9d78b9dd922f)

## Establishing SSH Connection to the EC2 Instance in AWS Console

![Screenshot (634)](https://github.com/user-attachments/assets/6f6f55d8-8ca2-4e50-a3ee-09336700c79a)

## Deploying the Web Application

![Screenshot (635)](https://github.com/user-attachments/assets/ca501fe5-7d34-4e11-82d2-8f9c769f94af)



