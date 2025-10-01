# Smart Retail Customer Insights Tracker – Salesforce Project

## Problem Statement
Retail stores often struggle to track customer purchases and loyalty.
This project provides a Salesforce app to manage customers, calculate loyalty points, update tiers automatically, send thank-you emails, and visualize customer insights with dashboards.

## Solution
The Smart Retail Customer Insights Tracker centralizes customer management.
It allows:
Customer & product record creation
Purchase tracking with automatic total calculation
Loyalty points & tier updates (Bronze, Silver, Gold)
Automated Gold-tier emails

---

##  Project Phases

### **Phase 1: Problem Understanding & Requirement Gathering**
- Identified business problem: Retailers need to **track customer purchases, loyalty points, and tiered benefits**.  
- Defined project scope: Customer Object, Purchase Object, Loyalty automation.  
- Outlined functional and non-functional requirements.  

---

### **Phase 2: Salesforce Setup & Object Creation**
- Created Salesforce Developer Org.
- Set up environment for objects, fields, and automation.  

---

### **Phase 3: Data Modeling & Relationships**
- Objects created: Customer, Product, Purchase.
- Key fields: Name, Email, Phone, Loyalty Points, Tier, Price, Quantity, Total Amount (formula).
- Configured **Lookup Relationships** between Customers and Purchases.
  
---

### **Phase 4: Process Automation (Flows)**
- Built **Record-Triggered Flow** on Purchase creation:  
  - Automatically update **Customer’s Loyalty Points**.  
  - Update **Tier** based on points (Gold,Silver,Bronze).  
  

---

### **Phase 5: Communication Automation (Gold Tier Email Flow)**  
- Created Flow to send **automatic congratulatory email** when Customer Tier = Gold.  
- Ensured email delivery settings & flow activation.  

---

### **Phase 6: User Interface Development**
- Created **Custom Lightning App: Smart Retail Tracker**.  
- Configured **Customer Page Layout** (Details + Loyalty Info).  
- Added **Custom Button: Add Purchase** for quick record creation.  
- Verified smooth integration with Loyalty Flow.  

---

### **Phase 7: External Access / UI Enhancement**
- Designed **Lightning Record Page for Customer** with:  
  - Highlights Panel (Loyalty Points, Tier)  
  - Related Lists (Purchases)  
  - Record Detail  
- Assigned page defaults based on Profiles.  
- Integrated Flows and Buttons for direct interaction.  

---

### **Phase 8: Data Import & Validation**
- Imported sample data using **Data Import Wizard**.  
- Validated Customers and Purchases.  
- Ensured Loyalty Points & Tier updated automatically.  
- Verified Total Amount field with calculations.
- Validated data integrity and tested automation.

---

### **Phase 9:Reporting, Dashboards & Security Reviews**
Reports:
- Customer Sales Summary (Bar Chart)
- Gold Tier Customers (Pie Chart)
- Purchase Summary (Table)
Dashboard:
- combined Bar, Pie, Table with filters.
Security: verified profiles & sharing rules. 
- Built Dashboards for quick visualization of retail performance.  

---

### **Phase 10: Deployment & Demo Preparation**
- Prepared ** demo video, and documentation**.  
- Verified Flows, and UI Pages.
- Ensured end-to-end flow works:  
  - Add Purchase → Loyalty Points Update → Tier Upgrade → Email Notification → Reporting  

---

## ✅ Key Outcomes
- Automated **Customer Loyalty Management** system.  
- Seamless **UI for managing Customers and Purchases**.  
- Tier-based communication with **Flows**.  
- Insightful **Reports & Dashboards** for decision-making.  
- Fully functional **Salesforce app** ready for demo.  

---

##  Demo Video link
*https://drive.google.com/file/d/1E0yjUUO1E39HiiqB8ccoYaq046zC3B0g/view?usp=drive_link*  

---

##  Tech Stack
- **Platform:** Salesforce  
- **Admin Tools:** Objects, Fields, Relationships, Page Layouts, Lightning Pages  
- **Automation:** Record-Triggered Flows 
- **Reporting:** Standard Reports & Dashboards  
- **UI:** Lightning App Builder, Custom Buttons  

---

##  Author
**Pusarla Manaswini**


