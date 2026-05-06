# Cloud_Server_Setup_AWS
Cloud server setup and security configuration for a free tier AWS Debian VM

# AWS EC2 Instance Setup

Documentation for the virtual machine setup on AWS.

## Instance Overview
![Instance Details](documents/AWS_Instance.PNG)

## Security Configuration
* **Inbound Rules:** Restricted to SSH (Port 22) from my local IP.

![Security Group](documents/Security_Details.PNG)

## Connection Verification
Successfully connected via SSH using Windows Terminal.

![SSH Connection](documents/Connect_to_VM.PNG)

## Update and Upgrade Verification
The system is confirmed to be up-to-date after running sudo apt update && sudo apt upgrade -y. Output confirms 0 packages needing upgrade.

![Update and Upgrade](documents/VM_Update.PNG)
