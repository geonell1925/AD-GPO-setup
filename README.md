# AD-GPO-setup
# Active Directory Home Lab (Windows Server 2022)

## Overview

This project demonstrates the deployment of an **Active Directory (AD) Home Lab** using **Windows Server 2022** in **VMware Workstation**. The lab simulates a small enterprise environment by configuring a Domain Controller, creating Organizational Units (OUs), managing users and computers, and implementing Group Policy Objects (GPOs) for centralized administration.

## Objectives

* Deploy Windows Server 2022 as a Domain Controller
* Install and configure Active Directory Domain Services (AD DS)
* Configure DNS for the domain
* Create Organizational Units (OUs)
* Manage domain users, computers, servers, and security groups
* Apply Group Policy Objects (GPOs) to enforce security settings
* Join a Windows 11 client to the domain

## Lab Environment

* **Hypervisor:** VMware Workstation
* **Server OS:** Windows Server 2022
* **Client OS:** Windows 11 Pro
* **Domain:** `geonell1925.local`
* **Domain Controller:** `DC01`

## Configuration

### Active Directory

* Installed Active Directory Domain Services (AD DS)
* Promoted the server to a Domain Controller
* Configured an Active Directory-integrated DNS server
* Created the `homelab.local` domain

### Organizational Units (OUs)

* Users
* Computers
* Servers
* IT Department
* HR Department
* Finance Department
* Security Groups
* Distribution Groups

### User and Computer Management

* Created multiple domain user accounts
* Organized users into department-specific OUs
* Added Windows 11 client computers to the domain
* Created server objects for administrative management
* Configured security groups for role-based access

### Group Policy Objects (GPOs)

Implemented several Group Policies, including:

* Password complexity and password history
* Account lockout policy
* Desktop wallpaper deployment
* Disable Control Panel
* Disable Command Prompt
* USB storage restrictions
* Windows Defender configuration
* Windows Update settings
* Screen lock and inactivity timeout

### Validation

* Verified successful domain authentication
* Confirmed DNS name resolution
* Joined Windows 11 client to the domain
* Applied policies using `gpupdate /force`
* Verified GPO application with `gpresult /r`

## Skills Demonstrated

* Windows Server 2022 Administration
* Active Directory Domain Services (AD DS)
* Domain Controller Deployment
* DNS Administration
* Organizational Unit Management
* User and Group Administration
* Group Policy Management
* Windows 11 Domain Join
* Identity and Access Management (IAM)
* Enterprise Windows Administration

## Technologies Used

* Windows Server 2022
* Windows 11 Pro
* VMware Workstation
* Active Directory Domain Services (AD DS)
* DNS Server
* Group Policy Management Console (GPMC)

## Screenshots

<img width="1132" height="632" alt="ad" src="https://github.com/user-attachments/assets/7163b8ab-a6f6-4dd4-9836-d8916df47839" />
<img width="861" height="479" alt="AD2" src="https://github.com/user-attachments/assets/73e8e61f-8db6-4016-9a97-f6f92ca1905d" />
<img width="922" height="571" alt="AD1" src="https://github.com/user-attachments/assets/db3780d9-9714-4afa-b1e0-5d98779de8c1" />
<img width="878" height="429" alt="AD3" src="https://github.com/user-attachments/assets/2885bbbe-d483-4b7d-821a-ae5ebbb174ea" />
<img width="1010" height="571" alt="ad4" src="https://github.com/user-attachments/assets/2114271f-4d13-444a-87b2-0c4582742945" />
<img width="799" height="480" alt="ad6" src="https://github.com/user-attachments/assets/97ff5b10-7876-4794-bcc1-d9b21df216d2" />
<img width="861" height="430" alt="ad5" src="https://github.com/user-attachments/assets/477827f3-51fb-4946-a44b-dab3fe9a15a4" />


```

## Conclusion

This Active Directory Home Lab demonstrates the deployment and administration of a Windows Server 2022 domain environment. The project showcases core enterprise IT administration tasks, including Active Directory configuration, user and computer management, Group Policy implementation, and centralized identity management, providing hands-on experience relevant to System Administration, IT Support, and SOC Analyst roles.
