# Hyper-V & Windows Server 2022 — Active Directory Lab

## Project Overview

This project demonstrates the deployment and administration of a virtualized Windows Server 2022 infrastructure using Microsoft Hyper-V.

The lab simulates a small business IT environment with centralized identity management, file sharing, Group Policy, access control, and backup and recovery.

## Lab Infrastructure

| Virtual Machine | Operating System | Role |
|---|---|---|
| DC2022 | Windows Server 2022 | Domain Controller, Active Directory, DNS |
| FILE01 | Windows Server 2022 | File Server, Backup |
| CLIENT01 | Windows 11 | Domain-joined workstation |

**Virtualization platform:** Microsoft Hyper-V

## Technologies and Skills

- Microsoft Hyper-V
- Windows Server 2022
- Active Directory Domain Services (AD DS)
- DNS configuration and troubleshooting
- Organizational Units (OU)
- User accounts and security groups
- Group Policy Objects (GPO)
- NTFS and share permissions
- Network drive mapping
- Volume Shadow Copies
- Windows Server Backup

## Practical Scenarios

### 1. Active Directory Administration
- Created departmental Organizational Units: IT, RH, Direction.
- Configured user accounts and security groups.
- Joined a Windows 11 workstation to the domain.

### 2. File Server Administration
- Created shared folders for different departments.
- Configured NTFS and share permissions.
- Tested departmental access restrictions.

### 3. Group Policy Management
- Configured automatic network drive mapping.
- Applied user restrictions through GPO.
- Verified policy application on Windows 11.

### 4. Backup and Recovery
- Configured Volume Shadow Copies.
- Tested recovery of accidentally deleted files.
- Installed Windows Server Backup.
- Added a separate virtual disk for backup storage.

## Project Purpose

This hands-on project was developed to strengthen practical skills in Windows Server administration, IT infrastructure management, troubleshooting, and technical support.

## Screenshots

Screenshots of the infrastructure and configurations will be added to demonstrate the implementation and testing of each component.
