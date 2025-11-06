# Windows Server 2022 Vitural Lab Setup

## Overview
This project demonstrates a hands-on setup of a Windows Server 2022 Active Directory environment in a virtualized lab.  
The goal was to practice system administration skills such as domain management, user/group creation, and Group Policy configuration, and Azure AD integration.   


## Tools & Technologies
- Platform: VirtualBox
- Server OS: Windows Server 2022
- Clent OS:Windows 11 Pro
- Domain Name: cjohnson.local
- Active Directory
- Group Policy Objects (GPO)
- Azure AD Connect

## Lab Setup and Key Configurations
  # 1. Virutal Environment Setup
  - Installed and configured VirtualBox
  - Created two virtual machines:
    - Server: Windows Server 2022 (Domain Controller)
    - Client: Windows 11 jointed to the domain.

  # 2. Active Directory and Domain Setup
  - Windows Server 2022 to a Domain Controller
  - Added windows 11 clients to cjohnson.local domain

  # 3. User and Group Management
  - Created Active Directory template accounts with custom properties
  - Created organization units (OUs) for different departments. 

  # 4. Group Policy Management 
    - Created and linked Group Policy Objects (GPOs) to enforce:
      - Password requirements
      - Wallpaper settings
      - Login banners
# 5. Azure AD Integration 
  - Installed and configured Azure AD Connect.
  - Implemented hybrid Azure AD join and seamless single sign on (SSO) using password hash sync.

## Troubleshooting and Problem Solving Log
This section focuses on the key issues I encountered during the lab and how i resolved them. 

  Issue

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
