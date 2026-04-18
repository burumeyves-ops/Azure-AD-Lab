# Azure-AD-Lab
Documentation on how to create lab on Azure
# Azure IAM Lab

> Hands-on Microsoft Azure and Identity & Access Management lab focused on Azure VM deployment, Windows Server Active Directory, Microsoft Entra ID concepts, and PowerShell automation.

## Project Overview

This repository documents my step-by-step IAM lab in Microsoft Azure. The goal of this project is to build practical skills in identity and access management by creating and managing a Windows Server virtual machine, installing Active Directory Domain Services, learning Microsoft Entra ID concepts, and later automating identity tasks with PowerShell. [Add your screenshots and notes as you progress.]

This lab is designed as a learning project and portfolio project. It shows not only the final setup, but also the decisions, challenges, troubleshooting steps, and lessons learned during the process.

## Project Goals

- Learn the fundamentals of Microsoft Azure
- Create and configure a Windows Server VM in Azure
- Connect to the VM using Remote Desktop
- Install and configure Active Directory Domain Services
- Create an Active Directory lab structure with OUs, users, and groups
- Learn the relationship between on-prem Active Directory and Microsoft Entra ID
- Practice role assignment and access control concepts
- Study Conditional Access policies in a lab context
- Simulate onboarding and offboarding processes
- Build PowerShell scripts for IAM-related administration tasks

## Skills Demonstrated

- Azure administration
- Windows Server administration
- Active Directory Domain Services
- Identity and Access Management fundamentals
- Microsoft Entra ID concepts
- Group-based access control
- PowerShell scripting
- Technical documentation
- Troubleshooting and lab planning

## Technologies Used

- Microsoft Azure
- Windows Server
- Active Directory Domain Services
- Microsoft Entra ID
- Remote Desktop Protocol (RDP)
- PowerShell
- GitHub
- Markdown

## Lab Roadmap

### - [Phase 1: Azure Foundation](./docs/01-azure-foundation.md)
In this phase, I learned the Azure portal layout and built the base environment for the lab. This included creating the resource group, virtual network, subnet, security settings, and Windows Server virtual machine.

### Phase 2: Windows Server VM Deployment
In this phase, I connected to the VM using RDP, reviewed basic Windows Server management, and prepared the machine for Active Directory installation.

### Phase 3: Active Directory Domain Services
In this phase, I installed AD DS, promoted the VM to a domain controller, and verified that the required Active Directory management tools were working.

### Phase 4: AD Structure
In this phase, I created a simple organizational unit structure, added users and groups, and documented how access can be managed through group-based administration.

### Phase 5: Microsoft Entra ID Concepts
In this phase, I studied the differences between Active Directory and Microsoft Entra ID, explored role assignment concepts, and documented how cloud identity fits into IAM.

### Phase 6: Access Control and Governance
In this phase, I documented role assignments, authorization flow concepts, Conditional Access basics, and simulated onboarding and offboarding processes.

### Phase 7: PowerShell Automation
In this phase, I began scripting IAM tasks such as bulk user creation, disabling inactive accounts, and automating repetitive identity administration work.

## Repository Structure

```text
azure-iam-lab/
│── README.md
│── docs/
│   │── 01-azure-foundation.md
│   │── 02-vm-deployment.md
│   │── 03-active-directory-install.md
│   │── 04-ou-users-groups.md
│   │── 05-entra-id-notes.md
│   │── 06-role-assignment.md
│   │── 07-conditional-access.md
│   │── 08-onboarding-offboarding.md
│   │── 09-powershell-automation.md
│── scripts/
│   │── create-50-users.ps1
│   │── disable-inactive-users.ps1
│   │── role-assignment-automation.ps1
│── images/
│   │── azure-vm-creation.png
│   │── rdp-connection.png
│   │── ad-ds-install.png
│   │── ad-structure.png
│   │── entra-role-notes.png
```

## Documentation Format

For each phase, I document the following:

- Objective
- Environment used
- Step-by-step actions taken
- Screenshots
- Result
- Problems encountered
- Troubleshooting performed
- Key lessons learned

## Key Concepts Covered

### Azure Virtual Machines
Azure VMs provide the infrastructure layer for running Windows Server in a cloud environment. In this project, the VM is the base platform used to install and manage Active Directory Domain Services.

### Active Directory Domain Services
AD DS provides identity and directory services for user accounts, groups, computers, and authentication inside a Windows domain environment.

### Microsoft Entra ID
Microsoft Entra ID is Microsoft’s cloud identity platform. In this lab, I am learning how it differs from traditional Active Directory and how cloud-based access control fits into IAM.

### IAM Operations
This project also focuses on common IAM workflows such as user provisioning, deprovisioning, group-based access, role assignment, and access policy review.

## Screenshots

Add screenshots here as you complete each section.

Example:
- Azure resource group and VM creation
- RDP login to Windows Server
- Server Manager showing AD DS installation
- Active Directory Users and Computers console
- OU and group structure
- PowerShell scripts running successfully

## Lessons Learned

- Azure networking and VM planning are important before installing server roles
- Active Directory depends heavily on correct DNS and domain configuration
- Group-based administration is more scalable than assigning permissions directly to users
- IAM work combines infrastructure, identity design, access control, and automation
- Documentation is important because it proves both technical work and problem-solving ability

## Challenges and Troubleshooting

Use this section to document real issues you run into.

Example entries:
- RDP connection failed because of NSG or firewall settings
- DNS was not configured correctly after promoting the server
- User creation script needed input validation
- Group membership did not apply as expected until replication or policy refresh

## Future Improvements

- Add a second VM to simulate domain join scenarios
- Expand PowerShell scripts with logging and error handling
- Add more detailed Entra ID role assignment examples
- Document Conditional Access lab scenarios
- Create a simple identity lifecycle workflow diagram

## Why This Project Matters

This project helps demonstrate practical IAM skills in a lab environment. It shows experience with Azure, Windows Server, Active Directory, access control concepts, and PowerShell automation, while also showing the ability to document technical work clearly for future employers and collaborators.

## Author

**Your Name**  
Aspiring IAM / IT Infrastructure Professional  
[LinkedIn Profile](#)  
[GitHub Profile](#)
