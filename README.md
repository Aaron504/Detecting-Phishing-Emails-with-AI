# Detecting-Phishing-Emails-with-AI
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 11 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- PHASE 1: Create the Phishing Email Dataset
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

PHASE 1: Create the Phishing Email Dataset

This Python script creates a small, structured dataset to simulate phishing and legitimate emails. It uses basic examples of email text and labels them as either phishing (1) or legitimate (0). The script stores the dataset in a CSV file (emails.csv), which will be used to train a machine learning model.

Purpose:
To provide a simple, controlled dataset to train and test a phishing email detection algorithm.

Key Features:

- Manually created email samples mimicking real-world phishing and safe email content

- Binary labels: 1 for phishing, 0 for legitimate

- Output stored in a CSV file for easy use in model training

![Screenshot 2025-05-17 194518](https://github.com/user-attachments/assets/a757e384-f178-46c9-b44e-1d98f06e8898)
![Screenshot 2025-05-17 200448](https://github.com/user-attachments/assets/0131e4aa-a585-4cc9-98c6-7ca1ff5b09c9)

