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

Screenshots will be added after deployment.

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
