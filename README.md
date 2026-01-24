# Instant Recovery Monitoring System

A workflow-based monitoring and notification system built using Microsoft Power Platform.

## 🔹 Project Overview
The Instant Recovery Monitoring System is a workflow-based solution built using:
- Microsoft Power Apps
- Power Automate
- SharePoint Online
- Microsoft Outlook (Email Integration)

It automates the process of recording, tracking, and notifying instant recovery test results for virtual machines (VMs) in IT infrastructure environments.

---

## 🎯 Objectives
- Automate recovery test monitoring and reporting
- Ensure accurate tracking of backup and restore operations
- Centralize data storage using SharePoint
- Enable IT members to submit recovery data easily
- Automatic email notifications to management
- Color-coded status reporting
- Full audit trail for compliance and reporting

---

## 🧰 Technologies Used
- Power Apps
- Power Automate
- SharePoint Online
- Microsoft Outlook
- Microsoft 365

---

## 🏗️ System Architecture

Power Apps ➜ SharePoint ➜ Power Automate ➜ Email Notification

---

## 📂 Project Structure


---

## 🧾 SharePoint List Structure

| Field Name | Type | Description |
|------|------|------------|
| Date | Date/Time | Entry date |
| IT Member | Person | Auto captured user |
| VM Name | Text | VM Name |
| Backup Date | Date/Time | Last backup date |
| Restore Test Date | Date/Time | Restore test date |
| Status | Choice | Successful / Warning / Failed |
| Comment | Multiple lines | Notes |
| Attachments | File | Evidence |

---

## 🔁 Workflow Logic

1. IT user submits recovery form via Power Apps  
2. Data stored in SharePoint  
3. Power Automate triggers automatically  
4. Status-based condition logic runs  
5. HTML formatted email is generated  
6. Notification sent to managers  
7. Data stored for reporting and auditing  

---

## 📧 Email Notification Logic

| Status | Color | Notification Type |
|------|------|------|
| Successful | Green | Info |
| Warning | Orange | Alert |
| Failed | Red | Critical Alert |

---

## 📈 Future Enhancements
- Power BI dashboard integration
- Approval workflows
- SLA tracking
- Automated escalation
- Incident management integration

---

## 👨‍💻 Author
**Youssef Madian**  
IT Infrastructure Engineer  

---
