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
