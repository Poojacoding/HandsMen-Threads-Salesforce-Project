# 🧵 HandsMen Threads: Elevating Sophistication in Men's Fashion (Salesforce Project)

This project is a Salesforce implementation for **HandsMen Threads**, a dynamic organization in the fashion industry. It focuses on **data management**, **customer engagement**, and **workflow automation** to streamline operations and elevate customer experience.

---

## 🚀 **Project Overview**

HandsMen Threads aims to:
- Build a **robust data model** for business data.
- Maintain **data integrity** directly from the UI.
- Automate key business workflows for better efficiency.

The system includes:
- Automated Order Confirmations
- Dynamic Loyalty Program updates
- Proactive Stock Alerts
- Scheduled Bulk Order Processing

---

## 🛠 **Key Features**

✅ **Data Model**
- Custom objects: `Order__c`, `Inventory__c`, `HandsMen_Customer__c`
- Lookup relationships for seamless data flow

✅ **Business Processes**
- **Order Confirmation Email**: Automatically sent to customers on order placement
- **Loyalty Program Updates**: Customer loyalty levels (Gold, Silver, Bronze) updated daily based on purchase history
- **Stock Alerts**: Inventory managers notified when stock drops below thresholds
- **Scheduled Inventory Sync**: Updates processed at midnight daily

✅ **Automation Tools**
- Record-Triggered Flows
- Scheduled Flows
- Apex Triggers
- Classic Email Templates with Letterheads

---

## 📂 **Folder Structure**

force-app/main/default/
├── apex/ # Apex Classes & Triggers
├── objects/ # Custom Objects & Fields
├── workflows/ # Workflow Rules
├── flows/ # Lightning Flows
├── emailTemplates/ # Classic Email Templates
└── layouts/ # Page Layouts

---

## 🖥 **Demo**
👉 **[Live Demo (Video)](https://drive.google.com/file/d/1L0qQYZGBCgFLcgACZNpGa4ZTO0G4IJpx/view?usp=sharing)**  
👉 **[GitHub Repository](https://github.com/Poojacoding/HandsMen-Threads-Salesforce-Project)**  

---

## 📧 **Email Templates**
- ✅ Order Confirmation
- ✅ Low Stock Alert
- ✅ Loyalty Program Update

---

## 📜 **Technologies Used**
- Salesforce Platform
- Salesforce Apex
- Lightning App Builder
- Salesforce Flows
- Classic Email Templates
- GitHub (Version Control)

---

## 👩‍💻 **How to Deploy**
1. Clone the repository:  
   ```bash
   git clone https://github.com/Poojacoding/HandsMen-Threads-Salesforce-Project.git

2. Authorize your Salesforce Org:

   ```bash
   sf org login web -a <your-org-alias>
   
3. Push metadata to Salesforce:

   ```bash
   sf project deploy start --manifest manifest/package.xml
   
🙌 Author
👤 Pooja Soni
📧 Email: [your-email@example.com]
🌐 LinkedIn: Your LinkedIn Profile

⭐ Acknowledgements
This project was developed as part of a Salesforce learning journey.
Special thanks to mentors and the Salesforce community.

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
