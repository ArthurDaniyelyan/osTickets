<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

# osTicket Deployment on Microsoft Azure

## Project Overview
This project showcases the deployment and configuration of osTicket, an open-source ticketing system, on Microsoft Azure. The goal of this setup is to demonstrate proficiency in setting up a help desk system using cloud infrastructure, configuring necessary services, and troubleshooting common issues.

## Skills Demonstrated
- Cloud deployment using Microsoft Azure
- Virtual Machine setup and configuration
- Installation and configuration of IIS, PHP, and MySQL
- osTicket installation and basic configuration
- Troubleshooting and problem-solving

## Deployment Steps

### 1. Setting Up the Azure Virtual Machine
- Created a Windows Server VM in Microsoft Azure.
- Configured network security groups to allow necessary ports (HTTP, HTTPS, RDP).

### 2. Installing Required Components
- Installed and configured **Internet Information Services (IIS)**.
- Installed **PHP** and configured it for IIS.
- Installed **MySQL** and created a database for osTicket.

### 3. osTicket Installation
- Downloaded and extracted osTicket files into the IIS web directory.
- Configured **PHP extensions** and adjusted IIS settings.
- Ran the osTicket installer and connected it to the MySQL database.

### 4. Post-Installation Configuration
- Created user roles and permissions.
- Tested the system to ensure proper ticket creation and management.

## Lessons Learned
- Gained hands-on experience with Azure cloud services.
- Learned how to configure IIS for web applications.
- Improved troubleshooting skills when dealing with server-related issues.

