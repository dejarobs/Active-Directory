# Active Directory Home Lab

## Overview

This project demonstrates the deployment and administration of an enterprise Active Directory environment hosted in Microsoft Azure.

The lab includes configuring a Windows Server Domain Controller, joining a Windows 11 client to the domain, managing users and groups, configuring Group Policy, implementing NTFS permissions, reviewing Windows Security events, performing PowerShell administration, and documenting the entire deployment.

## Objectives

- Install Windows Server 2022
- Configure a Domain Controller
- Install Active Directory Domain Services (AD DS)
- Create Organizational Units (OUs)
- Create and manage users and groups
- Join Windows 11 to the domain
- Configure Group Policy Objects (GPOs)
- Document the lab with screenshots

## Lab Environment

- Cloud Platform: Microsoft Azure
- Domain Controller: Windows Server 2025
- Client Machine: Windows 11
- Domain: adlab.local
- Services:
  - Active Directory Domain Services
  - DNS
  - Group Policy
  - PowerShell

## Technologies Used

- Microsoft Azure
- Windows Server 2025
- Windows 11
- Active Directory Domain Services
- DNS
- Group Policy
- PowerShell
- Windows Event Viewer
- NTFS Permissions
- Git
- GitHub

## Project Status

🟢 Completed

## Repository Structure

```
Active-Directory/
│
├── README.md
├── Screenshots/
│   ├── 01-azure-infrastructure-CLIENT01.png
│   ├── 01-azure-infrastructure-DC01.png
│   ├── ...
│   └── 14-azure-vm-deallocated.png
│
├── Documentation/
│   ├── Active-Directory-Lab-Guide.pdf
│   ├── Commands.md
│   └── Lessons-Learned.md
│
└── Diagrams/
    └── Active-Directory-Network.png
```

## Skills Demonstrated

- Active Directory Administration
- Organizational Unit (OU) Management
- User and Group Administration
- Domain Join Operations
- DNS Configuration
- Group Policy Management
- NTFS Permissions
- Windows Security Event Analysis
- Authentication Auditing
- PowerShell Administration
- Azure Virtual Machine Management

## Project Walkthrough

01. Azure Infrastructure
02. Server Manager Configuration
03. Active Directory Users and Computers
04. Domain Join
05. Shared Department Folders
06. NTFS Permissions
07. Permission Validation
08. Group Policy Management
09. Successful Authentication (Event ID 4624)
10. Failed Authentication (Event ID 4625)
11. PowerShell – List Active Directory Users
12. PowerShell – Create and Verify Active Directory User
13. PowerShell Security Logs
14. Azure VM Deallocated

## Key Takeaways

Through this lab I gained hands-on experience deploying and administering an enterprise Active Directory environment in Microsoft Azure. I configured identity services, managed users and permissions, applied Group Policy, analyzed authentication events, and used PowerShell to administer the environment.
