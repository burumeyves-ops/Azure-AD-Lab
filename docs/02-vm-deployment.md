# Phase 2: Windows Server VM Access and Preparation

[← Back to main README](../README.md)

## Objective
Connect to the Azure Windows Server VM with Remote Desktop and prepare the server for Active Directory installation.

## What I Did
- Connected to the Azure VM using RDP
- Signed in with the local administrator account created during deployment
- Verified the server was accessible and working
- Reviewed basic Server Manager functions
- Prepared the VM for the next phase of Active Directory Domain Services installation

## Why This Matters
Before installing Active Directory Domain Services, I need to confirm that the VM is reachable, stable, and ready for server role configuration. This phase helps establish the base Windows Server environment that the rest of the IAM lab will depend on.

## Environment
- Platform: Microsoft Azure
- VM OS: [Enter your Windows Server version]
- Access Method: Remote Desktop Protocol (RDP)
- VM Name: [Enter VM name]
- Resource Group: [Enter resource group name]
- Region: [Enter Azure region]

## Step-by-Step Notes
1. Opened the Azure portal.
2. Navigated to **Virtual Machines**.
3. Selected my Windows Server VM.
4. Selected **Connect > RDP**.
5. Downloaded the RDP file.
6. Opened the RDP file on my local computer.
7. Entered the VM administrator username and password.
8. Logged in successfully to the Windows Server desktop.
9. Opened Server Manager.
10. Confirmed the VM was ready for the next phase.

## Verification
I confirmed this phase was successful by:
- Reaching the Windows login screen
- Signing in to the VM
- Seeing the Windows Server desktop
- Opening Server Manager without issues

## Screenshots
- Azure VM overview page
  <img width="1017" height="891" alt="Screenshot 2026-04-18 100112" src="https://github.com/user-attachments/assets/29dbe348-5df2-451f-bf67-103d497b22e8" />

- Connect > RDP screen
  <img width="1220" height="840" alt="Screenshot 2026-04-18 101709" src="https://github.com/user-attachments/assets/50baac50-dcfb-4c7d-87ab-a4ae5be27328" />

- Downloaded RDP connection prompt
  
- Windows Server login screen
   <img width="1908" height="923" alt="Screenshot 2026-04-18 101858" src="https://github.com/user-attachments/assets/7059f0bc-0f52-43a5-adf0-cf661e2413a0" />
- Windows Server desktop after sign-in
   <img width="1908" height="923" alt="Screenshot 2026-04-18 101858" src="https://github.com/user-attachments/assets/7059f0bc-0f52-43a5-adf0-cf661e2413a0" />
   
- Server Manager open on the VM
 


## Issues Encountered
- [Document any issue here]
- Example: RDP failed due to networking or port access
- Example: Login issue caused by incorrect username format

## Troubleshooting Performed
- Verified the VM was running
- Checked that RDP access was enabled
- Confirmed the VM had the required IP/connectivity
- Retried using the correct administrator account

## Key Learning
I learned how to remotely access a Windows Server VM in Azure and verify that it is ready for future server role configuration.

## Next Phase
Next, I will install **Active Directory Domain Services (AD DS)** on the VM and begin configuring the server as a domain controller.
