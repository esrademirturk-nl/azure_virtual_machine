# Azure Virtual Machine & Azure File Share Assignment

## 👩‍🎓 Student Information
**Name:** Esra Demirturk  
**Course:** Azure Fundamentals  
**Instructor:** (Trainer Name)  
**Date:** (Submission Date)

---

## 📌 Project Overview

This project demonstrates the creation and management of a Linux Virtual Machine in Microsoft Azure and the integration of Azure File Share.

The objective of this assignment was to understand:

- Virtual Machine deployment in Azure
- Network configuration (NSG rules)
- Web server installation and publishing
- Database installation and configuration
- Azure File Share creation and mounting using CIFS
- File operations between VM and Azure Storage

---

## ☁️ 1️⃣ Virtual Machine Creation

- Created a Linux (Ubuntu) Virtual Machine
- Configured authentication (username & password)
- Connected using Azure Bastion

---

## 🌐 2️⃣ Apache Web Server Installation

Installed Apache inside the Linux VM:

```bash
sudo apt update
sudo apt install apache2 -y
