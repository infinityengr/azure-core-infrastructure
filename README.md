# Azure Core Infrastructure Project

## Overview
Deployed a Linux virtual machine on Microsoft Azure and exposed a secure web service using nginx.

## Architecture
- Azure Virtual Machine (Ubuntu 24.04)
- Virtual Network and Subnet
- Network Security Group (NSG)
- Public IP
- Nginx web server

## What I Did
- Created an Azure VM inside a custom VNet
- Configured NSG rules for SSH (22) and HTTP (80)
- Connected using SSH key-based authentication
- Installed and managed nginx with systemd
- Customized the default web page
- Verified access via public IP

## Troubleshooting & Learning
- Resolved SSH access issues caused by restrictive NSG source IP rules
- Understood differences between Azure Cloud Shell and local SSH authentication
- Worked with Linux services using systemctl

## Result
A publicly accessible web server running on Azure.

## Screenshots

https://github.com/infinityengr/azure-core-infrastructure/tree/51700a7cd30f90e2d56168de423018bf28fab8c7/screenshots

