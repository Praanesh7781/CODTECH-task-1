Name : Praanesh S 

Company : CODTECH IT SOLUTIONS 

ID : CT4CC2700 

Domain : Cloud Computing 

Duration : June 20 to July 20 2024 

Mentor : Neela Santhosh kumar

**Project Overview**

**DEPLOYING A WEB APPLICATION ON AWS**

This project demonstrates the deployment of a simple web application using Amazon Web Services (AWS). The goal is to provide a foundational understanding of cloud deployment, covering essential tasks such as setting up a server, configuring a web application, and utilizing AWS services like EC2 and S3.

**Project Description**

In this project, you will learn how to deploy a web application on AWS through the following steps:

**Create an EC2 Instance:**

Log into the AWS Management Console.
Navigate to the EC2 Dashboard and click on "Launch Instance."
Choose an Amazon Machine Image (AMI), such as Amazon Linux 2.
Select an instance type, such as t2.micro, which is eligible for the free tier.
Configure instance details, ensuring to select the appropriate VPC and subnet.
Add storage if necessary.
Configure security groups to allow HTTP (port 80) and SSH (port 22) access.
Review and launch the instance, creating or selecting an existing key pair for SSH access.

**Upload Application Files to S3:**

Navigate to the S3 Dashboard in the AWS Management Console.
Create a new S3 bucket or choose an existing one.
Upload the web application files to the S3 bucket, ensuring proper folder structure.
Set appropriate permissions to allow the EC2 instance to access the files.

**Run the Instance using PuTTY:**

Download and install PuTTY if not already installed.
Convert the .pem key pair file to a .ppk file using PuTTYgen.
Open PuTTY and enter the public DNS or IP address of the EC2 instance.
Under Connection > SSH > Auth, browse and select the .ppk file.
Connect to the instance by clicking "Open" and log in as ec2-user.

**Load Application Files from S3 to the Server:**


Install the AWS CLI on the EC2 instance.
Configure the AWS CLI with your credentials.
Copy files from the S3 bucket to the EC2 instance using the appropriate AWS CLI commands.

**Unzip the Files:**


Install the unzip utility if not already installed.
Navigate to the directory where the files were copied.
Unzip the application files.

**Run the Web Application:**

Navigate to the application directory.
Ensure that all necessary dependencies and environment variables are set up.
Start the web application using the relevant command for your application.
Verify that the application is running by accessing the public IP address of the EC2 instance in a web browser.

**Technologies Used**

Amazon Web Services (AWS)

EC2

S3

PuTTY

AWS CLI

**Conclusion**

This project provides a hands-on approach to understanding the basics of deploying web applications on AWS. It covers essential skills in server setup, file management, and application deployment, serving as a valuable resource for anyone looking to get started with cloud computing.

![Screenshot (22)](https://github.com/Praanesh7781/CODTECH-task-1/assets/137862856/a3d48821-cf50-467f-a951-033d5c4dedc1)

![Screenshot (24)](https://github.com/Praanesh7781/CODTECH-task-1/assets/137862856/28fa49bb-919f-4039-bce8-078dd7a5189d)

![Screenshot (23)](https://github.com/Praanesh7781/CODTECH-task-1/assets/137862856/a184b5ab-c1df-461d-be12-37a5efc16ac5)
