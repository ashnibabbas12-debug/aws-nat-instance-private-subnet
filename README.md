# 🚀 AWS NAT Instance for Private Subnet

## 📌 Project Overview

This project demonstrates how to provide secure outbound internet access to EC2 instances located in a private subnet by using a custom Linux NAT Instance instead of an AWS NAT Gateway.

The goal is to reduce AWS networking costs while maintaining secure internet connectivity for backend servers.

---

# 🎯 Business Problem

AWS NAT Gateway provides internet access for private subnet resources but incurs a fixed monthly cost, even when traffic is minimal.

For small businesses, startups, and learning environments, a NAT Instance offers a more affordable alternative.

---

# ✅ Solution

I deployed:

- Amazon VPC
- Public Subnet
- Private Subnet
- Internet Gateway
- Linux NAT Instance
- Private EC2 Instance
- Route Tables
- Security Groups

The private EC2 instance accesses the internet through the NAT Instance while remaining inaccessible from the public internet.

---

# ☁ AWS Services Used

- Amazon EC2
- Amazon VPC
- Public & Private Subnets
- Internet Gateway
- Route Tables
- Security Groups

---

# 🛠 Skills Demonstrated

- AWS Networking
- Linux Administration
- Route Table Configuration
- Security Groups
- Cost Optimization
- High Availability Concepts

---

# 📸 Screenshots

# 📸 Project Screenshots

This folder contains screenshots documenting the implementation and verification of the **AWS NAT Instance for Private Subnet** project.

The images below demonstrate the complete configuration process, including installing required packages, configuring NAT, saving firewall rules, connecting to the private EC2 instance, and verifying outbound internet connectivity.

---

## 1. Amazon Linux Verification & Environment Setup

Verified the operating system and prepared the NAT Instance before configuration.

![Amazon Linux Verification](Screenshot%202026-07-06%20001111.png)

---

## 2. Installing Required Packages

Installed **iptables** and **iptables-services**, which are required to configure the EC2 instance as a NAT Instance.

![Installing Packages](Screenshot%202026-07-06%20001143.png)

---

## 3. Configuring Network Address Translation (NAT)

Configured the NAT Instance by creating the required **POSTROUTING MASQUERADE** rule using `iptables`.

![NAT Configuration](Screenshot%202026-07-06%20001241.png)

---

## 4. Saving Firewall Rules

Saved the iptables configuration to ensure the NAT rules persist after system reboot.

![Saving Rules](Screenshot%202026-07-06%20001300.png)

---

## 5. Verifying NAT Configuration

Confirmed that the NAT configuration was successfully applied.

![Verification](Screenshot%202026-07-06%20001310.png)

---

## 6. Connecting to the Private EC2 Instance

Successfully connected to the EC2 instance located in the private subnet through the NAT Instance.

![Private EC2 Connection](Screenshot%202026-07-06%20001325.png)

---

## 7. Internet Connectivity Test

Verified that the private EC2 instance could access the internet through the NAT Instance by successfully executing network connectivity tests.

![Internet Connectivity](Screenshot%202026-07-06%20001348.png)

---

## 8. Final Validation

Performed final verification to confirm that outbound internet access from the private subnet was working correctly without using an AWS NAT Gateway.

![Final Validation](Screenshot%202026-07-06%20001410.png)

---

## 9. Project Completion

Final project status after successful deployment and testing of the AWS NAT Instance architecture.

![Project Complete](Screenshot%202026-07-06%20001428.png)

---

# ✅ Project Outcome

This project successfully demonstrates:

- Cost optimization by replacing an AWS NAT Gateway with a Linux NAT Instance.
- Secure outbound internet access for EC2 instances in a private subnet.
- Configuration of `iptables` for Network Address Translation (NAT).
- Linux system administration on Amazon Linux.
- AWS VPC networking concepts, including public and private subnets.
- Route table configuration and secure network design.
- Verification of internet connectivity from private resources.

---

## 🛠 Technologies Used

- Amazon EC2
- Amazon VPC
- Public & Private Subnets
- Internet Gateway
- Route Tables
- Security Groups
- Amazon Linux 2023
- Linux
- iptables
- SSH

---

# 📚 Lessons Learned

- Difference between NAT Gateway and NAT Instance
- Configuring route tables
- Disabling Source/Destination Check
- Secure private subnet design
- Cost optimization using AWS networking services

---

# 👨‍💻 Author

Ashnab Abbas

Junior Cloud & DevOps Engineer
