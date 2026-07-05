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
