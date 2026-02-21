# Active Directory Home Lab

## Overview

In this lab I deployed and configued Active Directory on a Windows Server VM hosted in Microsoft Azure. 

Environment: Windows server 2025 - Windows 11 - Microsoft Azure

## What I Configured 
- Deployed Active Directory Domain Server (AD DS) on Windows Server in Azure
- Joined a Windows 11 client machine to the domain and configured DNS settings
- Created Organizational Units (OUs) to organize domain users
- Provisioned user accounts and managed group memberships
- Created and linked Group Policy Objects (GPOs) to enforce user access restrictions
- Troubleshoot authentication failures caused by disabled accounts and expired passwords

## Lab Walkthrough

Deployed AD DS on Windows Server and promoted to domain controller.

*insert pic*

---

Joined Windows 11 client to the domain and configured DNS to point to the domain controller.

*insert pic* 

---

Created Organizational Units and provisioned user accounts with appropriate group memberships.

*insert pic*

---

Created and linked a GPO to enforce acess restrictions across domain users.

*insert pic*

---

Resolved login failures caused by disabled accounts and expired passwords.

*insert pic*

---

## Results & Takeaways
- Learned how quickly small misconfigurations can lead into login failures for end users
- Better understood the relationship between DNS, domain membership, and authentication
- Group Policy proved to be a powerful tool for user management
- Troubleshooting in a live domain felt very close to real help desk scenarios


