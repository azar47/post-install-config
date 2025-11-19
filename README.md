<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket Logo"/>
</p>

# osTicket – Post-Install Configuration

This project demonstrates the post-installation configuration of the **osTicket Help Desk Ticketing System**.  
It walks through the administrative setup required to fully operationalize osTicket after installation, including roles, departments, teams, SLAs, agents, users, and help topics.

This repository is part of my final practical exam, built to demonstrate my ability to configure enterprise IT systems and document them clearly for employers and technical reviewers.

---

## 📌 **Project Summary**

### **What This Project Is**
A complete walkthrough and demonstration of configuring osTicket after installation.  
This includes:
- Admin Panel configuration  
- Role/department/team creation  
- SLAs  
- Help topics  
- User & agent management  

### **Languages Used**
- *None (GUI-based configuration)*

### **Environments Used**
- **Microsoft Azure** (Virtual Machine)  
- **Remote Desktop Protocol (RDP)**  
- **Internet Information Services (IIS)**  

### **Operating System**
- **Windows 10 Pro (21H2)**

### **Technologies / Applications**
- **osTicket v1.15+**  
- **IIS Web Server**  
- **PHP / MySQL Backend** (already installed prior to this configuration phase)


---

## 🧠 **Post-Install Configuration Objectives**
- Configure Admin & Agent Panels  
- Create Roles, Departments, and Teams  
- Configure global user settings  
- Create Agents (internal staff)  
- Create Users (customers)  
- Define SLAs and escalation timelines  
- Configure Help Topics for ticket routing  

---

# 🔧 **Configuration Steps (With Screenshots)**

> **Note:** Replace the “screenshot-X.png” paths with your uploaded GitHub image URLs.

---

## **1. Access the osTicket Admin & Agent Panels**
<p align="center">
  <img src="screenshot-1.png" width="80%" />
</p>
<p align="center"><i>Screenshot 1 — Logging into the Admin Panel at /scp/login.php</i></p>

---

## **2. Acknowledge the Difference: Admin Panel vs Agent Panel**
<p align="center">
  <img src="screenshot-2.png" width="80%" />
</p>
<p align="center"><i>Screenshot 2 — Admin Panel vs Agent Panel view</i></p>

---

## **3. Configure Roles (Permissions for Agents)**
**Location:**  
Admin Panel → Agents → Roles  
Create role: **Supreme Admin**

<p align="center">
  <img src="screenshot-3.png" width="80%" />
</p>
<p align="center"><i>Screenshot 3 — Supreme Admin role creation</i></p>

---

## **4. Configure Departments**
**Location:**  
Admin Panel → Agents → Departments  
Create department: **SysAdmins**

<p align="center">
  <img src="screenshot-4.png" width="80%" />
</p>
<p align="center"><i>Screenshot 4 — SysAdmins department</i></p>

---

## **5. Configure Teams**
**Location:**  
Admin Panel → Agents → Teams  
Create team: **Online Banking**

<p align="center">
  <img src="screenshot-5.png" width="80%" />
</p>
<p align="center"><i>Screenshot 5 — Online Banking team created</i></p>

---

## **6. Allow Users to Create Tickets**
**Location:**  
Admin Panel → Settings → User Settings  
Uncheck: **Require registration and login to create tickets**

<p align="center">
  <img src="screenshot-6.png" width="80%" />
</p>
<p align="center"><i>Screenshot 6 — Allowing unregistered ticket creation</i></p>

---

## **7. Create Agents (Internal Staff)**
**Location:**  
Admin Panel → Agents → Add New  
- Jane (Dept: SysAdmins)  
- John (Dept: Support)

<p align="center">
  <img src="screenshot-7.png" width="80%" />
</p>
<p align="center"><i>Screenshot 7 — Agent creation (Jane)</i></p>

---

## **8. Create Users (End Customers)**
**Location:**  
Agent Panel → Users → Add New  
- Karen  
- Ken  

<p align="center">
  <img src="screenshot-8.png" width="80%" />
</p>
<p align="center"><i>Screenshot 8 — Customer account creation</i></p>

---

## **9. Configure SLA Plans**
**Location:**  
Admin Panel → Manage → SLA  

Create SLAs:  
- **Sev-A** — 1 hour, 24/7  
- **Sev-B** — 4 hours, 24/7  
- **Sev-C** — 8 hours, Business Hours  

<p align="center">
  <img src="screenshot-9.png" width="80%" />
</p>
<p align="center"><i>Screenshot 9 — SLA configuration</i></p>

---

## **10. Configure Help Topics**
**Location:**  
Admin Panel → Manage → Help Topics  

Create:  
- Business Critical Outage  
- Personal Computer Issues  
- Equipment Request  
- Password Reset  
- Other  

<p align="center">
  <img src="screenshot-10.png" width="80%" />
</p>
<p align="center"><i>Screenshot 10 — Help Topics configuration</i></p>

---

# 📌 **Conclusion**
osTicket is now fully configured for real-world ticket handling.  
This setup allows agents to receive, categorize, and respond to user tickets using defined roles, SLAs, and routing rules.

---

# 📁 **How to Submit**
Copy/paste your repository link into the Practical Exam submission page.

Example:  
`https://github.com/azar47/post-install-config`
