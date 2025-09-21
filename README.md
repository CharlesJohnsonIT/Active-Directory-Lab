# Active-Directory-Lab
Hands On Active Directory lab setup and documentation

## Overview
This project demonstrates a hands-on setup of a Windows Server 2019 Active Directory environment in a virtualized lab.  
The goal was to practice system administration skills such as domain management, user/group creation, and Group Policy configuration.  

## Tools & Technologies
- VirtualBox
- Windows Server 2019
- Windows 10 Enterprise
- Active Directory
- Group Policy Objects (GPO)
- Azure AD Connect

## Lab Setup
1. Installed VirtualBox and created a Windows Server 2019 VM.  
2. Configured static IP, hostname, and promoted it to a Domain Controller.  
3. Joined Windows 10 clients to the domain.  
4. Created user accounts and organizational units (OUs).  
5. Applied and tested Group Policy Objects (password policy, desktop restrictions, mapped drives).  
6. Configured Azure AD Connect for hybrid join and single sign-on.  

## Key Takeaways
- Gained experience with domain setup and management.  
- Practiced troubleshooting domain join and policy application errors.  
- Improved understanding of hybrid AD integration with Azure.  

## Screenshots
![AD Users and Computers Screenshot](screenshots/ad-users.png)  
![Group Policy Screenshot](screenshots/gpo.png)  

## Next Steps
- Expand lab with DHCP and DNS roles.  
- Test user login scripts and automation with PowerShell.  
