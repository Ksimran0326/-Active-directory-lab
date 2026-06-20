# Active Directory Home Lab

## Overview

This project is a hands-on Active Directory home lab built using Windows Server in a virtual environment.

The goal of this lab was to understand how real enterprise environments manage users, security policies, file access, and system restrictions using Active Directory and Group Policy.

I used this lab to practice and test different configurations instead of just learning theory.

---

## What I Worked On

### Active Directory Basics
- Created and managed users and groups
- Organized users using Organizational Units (OUs)
- Understood domain vs local accounts

---

### Group Policy (GPO)
- Configured password and account lockout policies
- Restricted Control Panel access for users
- Blocked USB and removable storage devices
- Mapped network drives using Group Policy
- Tested policies on client machines
- Fixed issues when policies did not apply correctly

---

### File Sharing & Permissions
- Learned difference between NTFS and Share permissions
- Practiced Read, Write, and Full Control permissions
- Used inheritance and explicit permissions
- Created secure folder access for specific groups
- Tested real access scenarios with users

---

### File Server Resource Manager (FSRM)
- Created storage quotas for shared folders
- Set file screening rules to block unwanted file types
- Configured alerts for storage limits

---

### Advanced Security Policies
- Configured account lockout policies for failed login attempts
- Implemented Fine-Grained Password Policies (FGPP)
- Applied different password rules for different user groups
- Learned how policy precedence works

---

### Service Accounts & Kiosk Setup
- Created a service account for system use
- Configured automatic login for testing purposes
- Set up applications to start on boot
- Created a simple kiosk-style environment
- Applied restrictions using Group Policy

---

## Tools Used
- Windows Server (Active Directory Domain Services)
- Group Policy Management Console (GPMC)
- Windows 10 Client Machine
- File Server Resource Manager (FSRM)
- Sysinternals Suite (Autologon)
- VirtualBox / VMware

---

## Key Learning

- How Active Directory works in real environments
- How Group Policy controls users and computers
- How file permissions secure shared data
- How organizations apply different security rules for different users
- How testing and troubleshooting is important in IT environments

---

## Note

This is a learning project built in a virtual lab environment to practice Windows Server and Active Directory administration.
