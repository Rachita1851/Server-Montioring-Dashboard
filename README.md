# Server Monitoring Dashboard Using AWS EC2 & CloudWatch
# INTRODUCTION

"A real-time AWS-based server monitoring setup with alerting and visualization using EC2, CloudWatch, and SNS."

This project demonstrates how to set up a real-time cloud-based server monitoring system using AWS EC2 and Amazon CloudWatch. It provides insight into server health, including CPU usage, memory, disk activity, and network traffic, with automatic alarms and notifications.

# OBJECTIVES
•	Deploy an EC2 instance on AWS
•	Connect to the instance via SSH
•	Install and configure the CloudWatch Agent
•	Set up a CloudWatch dashboard for visual monitoring
•	Create alarms for critical metrics like CPU, disk, and network usage
•	Enable notifications using Amazon SNS
•	Test the monitoring setup by simulating load.

# Project Architecture Diagram
EC2 Instance -> CloudWatch Agent -> CloudWatch Dashboard & Alarms ->  SNS (Email Alerts)

# PROJECT SETUP
# Step 1: Launching EC2 Instance
•	Created an EC2 instance using the AWS Free Tier
•	Configured security groups to allow SSH access (port 22)
•	Connected to the instance using an SSH client
# Step 2: Installing and Configuring CloudWatch
•	Installed the CloudWatch Agent on the EC2 instance
•	Configured the agent to monitor:
o	CPU Utilization
o	Memory Usage
o	Disk I/O
o	Network Traffic
•	Created a CloudWatch Dashboard to view real-time metrics
# Step 3: Setting Up Alarms
•	Configured CloudWatch alarms for:
o	High CPU usage
o	Disk read/write operations
o	Network traffic spikes
•	Integrated Amazon SNS for sending alert notifications
•	Enabled logging to maintain a record of metrics and alerts. 


# TESTING THE SETUP
•	Simulated high CPU usage to trigger alarms
•	Generated network traffic to test NetworkIn and NetworkOut thresholds
•	Performed disk read/write operations
•	Verified real-time metrics and logs on the CloudWatch dashboard
•	Confirmed that SNS sent alerts when alarms were triggered.

# OUTCOME
A fully functional monitoring system that:
•	Visualizes key performance metrics in real-time
•	Automatically triggers alarms on threshold breaches
•	Sends notifications via Amazon SNS
•	Helps maintain server health and operational visibility

# Contact
For questions, feedback, or collaboration, feel free to connect:
•	GitHub: Rachita1851
•	Email: heyrachita@gmail.com







