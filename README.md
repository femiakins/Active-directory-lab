# Active-directory-lab

This repository documents my journey through ** hands-on IT support labs**, where I built a **Windows Server home lab** and practiced real-world **Help Desk / IT Support skills**.  

These labs mirror daily Tier 1 & Tier 2 tasks such as **Active Directory management, Group Policy, ticketing systems, and troubleshooting**.  

---

## 📚 Table of Contents
- [Lab 1–3: Environment Setup & Active Directory Basics](#lab-1-3-environment-setup--active-directory-basics)
- [Lab 4–6: User & Group Management, Shared Resources](#lab-4-6-user--group-management-shared-resources)
- [Lab 7–9: Group Policy & System Configurations](#lab-7-9-group-policy--system-configurations)
- [Lab 10–11: Software Deployment & Patch Management](#lab-10-11-software-deployment--patch-management)
- [Lab 12: Printers & Network Printing](#lab-12-printers--network-printing)
- [Lab 13: Ticketing Systems & Remote Support](#lab-13-ticketing-systems--remote-support)
- [Lab 14: Delegation & Account Lockout Troubleshooting](#lab-14-delegation--account-lockout-troubleshooting)
- [Key Takeaways](#-key-takeaways-labs-1-14)
- [Next Steps](#-next-steps)

---

## 🔧 Lab 1–3: Environment Setup & Active Directory Basics
- Installed and configured **Windows Server 2016/2019** in a VM.  
- Created a **domain controller** and joined Windows 10 clients to the domain.  
- Learned to use **Active Directory Users and Computers (ADUC)**.  
- Built an **Organizational Unit (OU) structure** for user and device management.  

**Skills gained:** Setting up a domain, joining clients, ADUC basics.  

---

## 👤 Lab 4–6: User & Group Management, Shared Resources
- Created user accounts, security groups, and OUs.  
- Practiced **password resets** and unlocking user accounts in AD.  
- Assigned **permissions for shared folders** (NTFS + share permissions).  
- Configured group membership for **access control and resource sharing**.  

**Skills gained:** User lifecycle management, security groups, access permissions.  

---

## ⚙️ Lab 7–9: Group Policy & System Configurations
- Deployed **Group Policy Objects (GPOs)** to manage desktops.  
- Applied GPOs for restrictions (disable Task Manager, control panel access).  
- Configured **drive mappings** via GPO.  
- Verified applied policies with **gpresult/RSOP**.  

**Skills gained:** Centralized policy management, troubleshooting GPO application.  

---

## 📦 Lab 10–11: Software Deployment & Patch Management
- Used **PDQ Deploy** to package and push software (e.g., Zoom, .NET).  
- Validated successful installs across multiple clients.  
- Practiced **remote deployment and update management**.  

**Skills gained:** Endpoint management, automation of software deployment.  

---

## 🖨️ Lab 12: Printers & Network Printing
- Installed a printer on the server and **shared it across the network**.  
- Added shared printer access to client machines.  
- Learned about **print spooler service**, drivers, and troubleshooting connectivity.  

**Skills gained:** Network printer setup, shared device management.  

---

## 🎫 Lab 13: Ticketing Systems & Remote Support
- Explored **Spiceworks Help Desk** (ticketing system).  
- Practiced **creating, assigning, documenting, and closing tickets**.  
- Simulated IT support workflows:  
  - Assigning tickets to the right team.  
  - Writing clear documentation in ticket notes.  
- Practiced **remote support** (screen sharing, privilege escalation, file transfer).  

**Skills gained:** Ticket management, ITSM processes, remote troubleshooting.  

---

## 🔑 Lab 14: Delegation & Account Lockout Troubleshooting
- Learned **delegation of control** in AD (e.g., allow a junior tech to only reset passwords).  
- Confirmed delegated permissions by logging in as restricted user.  
- Installed and used Microsoft’s **Account Lockout Status Tool** to:  
  - Check lockout events.  
  - Identify the source server/device causing failed logins.  
  - Troubleshoot cached credentials on mobile devices.  

**Skills gained:** Security best practices, account lockout troubleshooting, delegation of rights.  

---

## 🎯 Key Takeaways (Labs 1–14)
By completing these labs, I built skills in:  
✔ **Active Directory administration** (users, groups, OUs, delegation)  
✔ **Password resets and account unlocks**  
✔ **Group Policy creation and troubleshooting**  
✔ **File/print sharing and permissions**  
✔ **Software deployment (remotely) (PDQ Deploy)**  
✔ **Ticketing systems (Spiceworks)**  
✔ **Remote support and screen-sharing tools**  
✔ **Troubleshooting account lockouts with Microsoft tools**  
 

---

📌 *This project demonstrates my practical knowledge for IT Support / Help Desk roles by combining theory with hands-on labs.*
