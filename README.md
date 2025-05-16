# Inventory-Management
# 🧾 PowerApps Inventory Management System

A comprehensive **Inventory Management and Employee Lifecycle System** built using **PowerApps**, **SharePoint**, and **Power Automate**.

This system manages employee onboarding, offboarding, and asset assignments, and automates notifications, documentation, and tracking using 50+ Power Automate flows and 30+ connected SharePoint lists.

---

## 🚀 Features

### ✅ Employee Lifecycle Management
- **Onboarding**, **Offboarding**, and **Change/Replacement** workflows.
- Status-driven form navigation and asset reallocation.
- Automated PDF generation on submission for record-keeping.

### 💼 Asset Management
- Track laptops, docking stations, keyboards, and more.
- Use dropdowns/lookup fields filtered by availability (e.g., `instore = "Yes"`).
- Bulk upload of asset records directly into SharePoint.

### 🔁 Automations (Power Automate)
- 50+ flows automate:
  - PDF document creation and emailing
  - DOR (Date of Release) issuance
  - Notifications and record updates
  - Form-based triggers for each status

### 📁 Data Architecture
- 30+ SharePoint lists including:
  - `Onboarding List`
  - `Laptop Records`
  - `Docking Station`
  - `Employee Info`
  - `Assets Archive`
  - Others for specific asset types and lifecycle events

---

## 📂 Project Structure
## 🛠 Setup Instructions

1. **Import the App**  
   Go to [PowerApps Studio](https://make.powerapps.com) > Apps > Import package > Upload `InventoryApp.zip`

2. **Set Up SharePoint Lists**  
   Recreate the lists mentioned in `/SharePointLists/list_structure.md` or use exported list templates.

3. **Import Flows**  
   In [Power Automate](https://make.powerautomate.com), import each `.zip` flow from the `/PowerAutomate` folder and update connectors (Outlook, SharePoint).

4. **Configure Connections**  
   After import, configure all flows and app connections to match your environment (URLs, list names, email addresses, etc.)

---

## 📌 Notes

- This solution is designed for **internal IT and HR teams** managing employee transitions and hardware assignments.
- Flows are modular and reusable.
- Designed to support **scalable asset tracking**, **digital documentation**, and **audit compliance**.

---

## 🧑‍💻 Maintainer

> Created by Unukonda Saivandana  
> For queries or collaboration, feel free to contact
