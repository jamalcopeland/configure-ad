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
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Setup AD Infrastructure in Azure
- Setup Active Directory
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>



<h3>Step 1: Setup AD Infrastructure in Azure</h3>

![image](https://github.com/user-attachments/assets/78f3341d-6837-43de-8346-b8cf132953f3)

- Create virtual machines: client (Windows 10) & domain controller (Windows Server 2022)
- Create Virtual network and subnet
![image](https://github.com/user-attachments/assets/77735d12-14eb-4c91-ba58-6e3b3afd8a23)

- Configure the DNS server of client to the private IP Address of domain controller

<h3>Step 2: Install Active Directory Domain Services</h3>
-Setup a new forest

![image](https://github.com/user-attachments/assets/39ad9f81-46db-4461-9708-1bda291f2036)
-Install Active Directory

