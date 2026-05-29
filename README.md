# Windows Server & Active Directory Helpdesk Lab

## Project Overview
I built a virtual home lab environment to simulate a corporate IT infrastructure. The goal of this project was to gain hands-on experience with Active Directory management, user provisioning, and common Helpdesk troubleshooting scenarios.

## Tools & Technologies Used
* **Hypervisor:** Oracle VM VirtualBox
* **Operating System:** Windows Server 2022 (Evaluation Edition)
* **Directory Service:** Active Directory Domain Services (AD DS)

## Lab Setup & Architecture
1. Installed Oracle VM VirtualBox on my host gaming PC.
2. Configured a Virtual Machine with Windows Server 2022.
3. Promoted the server to a Domain Controller for the local domain: `Koka.local`.

## Helpdesk Scenarios Simulated
### 1. Active Directory User Provisioning
* Created an Organizational Unit (OU) structure for different departments (HR, IT, Sales).
* Generated 10 unique employee user accounts with standardized naming conventions.

<img width="1919" height="1022" alt="image" src="https://github.com/user-attachments/assets/091abffb-caa1-42c9-8450-4abdc91fbbed" />

### 2. Password Resets and Account Lockouts
* Simulated a user forgetting their password.
* Practiced unlocking accounts and forcing password changes at the next login.
<img width="1487" height="751" alt="image" src="https://github.com/user-attachments/assets/2993f51a-e2ea-4ed2-a7aa-e36bb682b3c7" />



## What I Learned
* How to navigate Windows Server Manager and Active Directory Administrative Center.
* The importance of clear documentation when resolving user access issues.
* How to troubleshoot virtual networks between a host machine and virtual machines.
