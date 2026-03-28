📌 Project Overview

This project demonstrates the implementation of a CI/CD (Continuous Integration and Continuous Deployment) pipeline using Jenkins Master-Agent architecture and AWS EC2.

The pipeline automates the process of building and deploying a web application (FoodExpress UI) directly on the server without containerization.

🎯 Objectives
Implement CI/CD pipeline using Jenkins
Understand Jenkins Master-Agent architecture
Automate build and deployment processes
Deploy application on AWS EC2
Gain practical DevOps experience
🧰 Tech Stack
☁️ AWS EC2 (Cloud Infrastructure)
🔁 Jenkins (CI/CD Automation)
🌐 Nginx (Web Server)
💻 HTML, CSS (Frontend Application)
🔗 GitHub (Version Control)
🏗️ Architecture

The project follows a DevOps pipeline:

Developer → GitHub → Jenkins Master → Jenkins Agent → EC2 Deployment → Browser Output

⚙️ Implementation
🔹 Day 1
Created AWS EC2 instances (Master & Agent)
Configured security groups (Ports: 22, 80, 443, 8080)
Installed Jenkins on Master node
Connected Jenkins Agent via SSH
Set up web server (Nginx) on EC2
Prepared web application files
🔹 Day 2
Created Jenkins pipeline job
Configured GitHub integration
Automated build process (pull code from repository)
Deployed application directly to EC2 server
Restarted Nginx service to reflect changes
Verified deployment via browser
🔄 CI/CD Pipeline Flow
Developer pushes code to GitHub
Jenkins Master triggers pipeline
Jenkins Agent executes build steps
Code is transferred to EC2 server
Application is deployed using Nginx
Output is accessed through browser
🖼️ Output
Jenkins pipeline executed successfully ✅
Application deployed on AWS EC2 ✅
Nginx serving the application successfully ✅
FoodExpress UI accessible via browser ✅
