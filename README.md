# Azure Active Directory Lab — Windows Server Administration & Security

## Project Overview

This project demonstrates the deployment and administration of an Active Directory environment hosted in Microsoft Azure. Using Windows Server 2022 and Windows 11 virtual machines, I configured a domain controller, managed domain users and computers, automated account creation with PowerShell, and performed common IT support and security troubleshooting tasks.

The lab simulates an enterprise IT environment where administrators manage employee identities, enforce account security policies, troubleshoot authentication issues, and monitor Windows security events.

## Technologies Used

- Microsoft Azure — Virtual Machines, Virtual Networks, and Network Interfaces
- Windows Server 2022 — Domain Controller (DC-1)
- Windows 11 Pro — Domain-Joined Workstation (Client-1)
- Active Directory Domain Services (AD DS)
- Active Directory Users and Computers (ADUC)
- DNS
- Group Policy Management Console (GPMC)
- Windows PowerShell ISE
- Windows Event Viewer
- Remote Desktop Protocol (RDP)

## Lab Objectives

1. Deploy and configure a Windows Server domain controller in Azure.
2. Join a Windows 11 workstation to the Active Directory domain.
3. Create and manage organizational units, domain users, and security groups.
4. Automate bulk employee account creation using PowerShell.
5. Configure account lockout policies through Group Policy.
6. Troubleshoot locked and disabled user accounts.
7. Investigate failed authentication attempts using Windows Event Viewer.

## Project Phases

### Phase 1 — Azure Infrastructure & Active Directory Deployment

Deploy Azure virtual machines, configure networking and DNS, install Active Directory Domain Services, create a new forest, and join a Windows 11 workstation to the domain.

### Phase 2 — User Administration & PowerShell Automation

Create administrative accounts, configure organizational units and security group memberships, manage Remote Desktop access, and automate employee account provisioning with PowerShell.

### Phase 3 — Account Security & Troubleshooting

Configure Group Policy account lockout settings, simulate account lockouts, reset passwords, disable and re-enable user accounts, and investigate authentication failures using Windows Event Viewer.

## Lab Environment

| Component | Configuration |
|---|---|
| Cloud Platform | Microsoft Azure |
| Domain Controller | DC-1 — Windows Server 2022 |
| Client Workstation | Client-1 — Windows 11 Pro |
| Active Directory Domain | mydomain.com |
| Virtual Network | Active-Directory-VNet |
| Resource Group | Active-Directory-Lab |
| Employee Organizational Unit | _EMPLOYEES |
| Administrator Organizational Unit | _ADMINS |

## Skills Demonstrated

- Windows Server administration
- Active Directory user and computer management
- DNS and network troubleshooting
- PowerShell scripting and automation
- Group Policy configuration
- Account provisioning and access management
- Password resets and account lockout troubleshooting
- Windows security event log analysis
- Remote Desktop configuration
- IT support troubleshooting and documentation

