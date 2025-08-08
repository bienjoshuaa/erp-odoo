# erp-odoo
A Modern ERP System built with Odoo (Python), React.js, and PostgreSQL.
# 🚀 FlexERP
A Modern ERP System built with **Odoo (Python)**, **React.js**, and **PostgreSQL**.

## 📌 Overview
FlexERP is a lightweight yet powerful ERP solution for small to medium-sized businesses.  
It integrates core business functions like sales, inventory, CRM, and reporting into a single role-based platform with a modern React.js frontend and an Odoo-powered backend.

---

## 📦 Modules & Features

### **1. Dashboard & Analytics**
- KPI cards (Sales, Expenses, Stock Count, Active Customers)
- Interactive charts (Sales trends, Top products, Inventory value)
- Alerts for low stock & overdue invoices

### **2. Inventory Management**
- CRUD for products & categories
- Stock in/out tracking
- Barcode scanning support
- Low-stock alerts & reorder suggestions
- Stock history logs

### **3. Sales Management**
- Create & manage sales orders
- Auto tax & discount calculations
- Invoice generation & payment tracking
- Order status updates
- PDF invoice export

### **4. CRM**
- Maintain customer profiles
- View purchase history
- Tag & categorize customers
- Search & filter customers

### **5. Reporting & Export**
- Sales reports (daily, monthly, custom range)
- Inventory valuation reports
- Customer activity reports
- CSV/PDF export

### **6. User & Role Management**
- Create and manage users
- Assign predefined roles
- Permission-based module access
- Audit logs for user actions

---

## 🔐 Roles & Permissions

| Role              | Sales | Inventory | CRM | Reports | User Mgmt | Approve Orders |
|-------------------|-------|-----------|-----|---------|-----------|----------------|
| **Admin**         | ✅    | ✅         | ✅  | ✅       | ✅         | ✅              |
| **Sales Manager** | ✅    | ❌         | ✅  | ✅       | ❌         | ✅              |
| **Inventory Manager** | ❌ | ✅         | ❌  | ✅       | ❌         | ❌              |
| **Sales Staff**   | ✅*   | ❌         | ✅* | ❌       | ❌         | ❌              |
| **Inventory Staff** | ❌ | ✅*        | ❌  | ❌       | ❌         | ❌              |

> *Limited permissions (e.g., create-only or view-only)

---

## 🛠 Tech Stack
- **Backend:** Odoo 17 (Python 3.10+)
- **Frontend:** React.js (Axios, Tailwind CSS, Recharts)
- **Database:** PostgreSQL
- **Integration:** Odoo REST API / JSON-RPC
- **Tools:** Docker, GitHub, Postman
- **Deployment:** Odoo.sh or VPS for backend, Vercel/Netlify for frontend

---

## 📂 Deliverables
- Fully functional ERP system with React frontend & Odoo backend
- Role-based authentication
- Responsive UI
- Documentation (Setup Guide, API Docs, User Manual)
- Demo video for portfolio

---
