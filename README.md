# Course-4-System-Administration-and-IT-Infrastructure-Services
# 📌 Project Overview

This project demonstrates the setup and configuration of a basic local web server using Microsoft Internet Information Services (IIS) on Windows.

The objective was to configure a working local server, create a simple hosted webpage, and understand how web services operate within an IT infrastructure environment.

# 🖥️ Technologies Used

*Windows Operating System

*Microsoft Internet Information Services (IIS)

*HTML and CSS (Static Web Page)

# ⚙️ Server Setup Process
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

# 🌐 Services Configured

Web Server (HTTP)

Default Website

Static Content Hosting

📂 Folder Structure

C:\inetpub
└── wwwroot
    └── index.html

# ✅ Outcome

The local IIS server successfully hosted a static web page.
This demonstrates:

Basic server configuration

Web service functionality

Understanding of server directory structure

Practical application of IT infrastructure concepts

# 🚀 Infrastructure Relevance

This setup simulates how web servers operate in enterprise and cloud environments such as Microsoft Azure and AWS. Understanding local server configuration builds foundational knowledge for cloud engineering and system administration roles.

# 📸 Screenshots Included

IIS installation enabled

IIS Manager console

Default IIS Welcome page

wwwroot directory

Custom webpage displayed in browser.

