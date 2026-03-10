# Course-4-System-Administration-and-IT-Infrastructure-Services
# Project Overview

This project demonstrates the setup and configuration of a basic local web server using Microsoft Internet Information Services (IIS) on Windows.

The objective was to configure a working local server, create a simple hosted webpage, and understand how web services operate within an IT infrastructure environment.

# Technologies Used

*Windows Operating System

*Microsoft Internet Information Services (IIS)

*HTML and CSS (Static Web Page)

#  Server Setup Process
# Step 1: Enable IIS

I enabled IIS through:

Control Panel → Programs → Turn Windows features on or off → Internet Information Services

After installation, the system was restarted to complete the setup.

# Step 2: Verify IIS Installation

I verified that the web server was running by accessing:

http://localhost

The default IIS welcome page confirmed successful installation.

# Step 3: Website Directory Location

The default web root directory for IIS is:

C:\inetpub\wwwroot

This directory stores all website files hosted by the server.

# Step 4: Create and Deploy a Web Page

Inside the wwwroot directory, I created a file named:

index.html

The file contains a basic HTML structure to test server functionality.

When accessing http://localhost in a web browser, the server successfully displayed the custom webpage.

# Services Configured

Web Server (HTTP)

Default Website

Static Content Hosting

📂 Folder Structure

C:\inetpub
└── wwwroot
    └── index.html

#  Outcome

The local IIS server successfully hosted a static web page.
This demonstrates:

<img width="1223" height="580" alt="image" src="https://github.com/user-attachments/assets/7e6b25c7-9a75-4d75-aa2f-f29872c2996c" />


Basic server configuration

Web service functionality

Understanding of server directory structure

Practical application of IT infrastructure concepts

# Infrastructure Relevance

This setup simulates how web servers operate in enterprise and cloud environments such as Microsoft Azure and AWS. Understanding local server configuration builds foundational knowledge for cloud engineering and system administration roles.

#  Screenshots Included

IIS installation enabled

IIS Manager console

Default IIS Welcome page

wwwroot directory

Custom webpage displayed in browser.

#  Conclusion

This project provided practical experience in configuring a basic web server using Microsoft Internet Information Services (IIS) on a Windows operating system. Through this setup, I gained an understanding of how web servers host and deliver web content to users through a browser.

By enabling IIS, locating the default web directory, and deploying a simple HTML webpage, I was able to successfully run a local server and verify that it was functioning correctly. This exercise also helped me understand important system administration concepts such as server configuration, directory structure, and web service deployment.

Overall, this project strengthened my foundational knowledge of IT infrastructure and demonstrated how web servers function in real-world environments. These skills are essential for roles in system administration, IT supprt and Cloud.

