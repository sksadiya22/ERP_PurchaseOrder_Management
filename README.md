# 📦 Purchase Order Management System Using SAP S/4HANA (SAP MM)

> An academic SAP S/4HANA Materials Management (MM) project demonstrating the complete **Purchase-to-Pay (P2P)** procurement lifecycle, from vendor creation to invoice verification.

![SAP](https://img.shields.io/badge/SAP-S%2F4HANA-0FAAFF?style=for-the-badge&logo=sap)
![Module](https://img.shields.io/badge/Module-SAP%20MM-success?style=for-the-badge)
![ERP](https://img.shields.io/badge/ERP-Procurement-orange?style=for-the-badge)

---

## 📖 Overview

This project demonstrates the implementation of a **Purchase Order Management System** using **SAP S/4HANA Materials Management (SAP MM)**.

The system automates the complete procurement process by integrating purchasing, inventory management, vendor management, and invoice verification into a centralized ERP platform.

The project follows the standard **Purchase-to-Pay (P2P)** business process used in modern enterprises.

---

# 🎯 Objectives

- Understand SAP S/4HANA MM
- Implement the Purchase-to-Pay (P2P) process
- Create and manage procurement documents
- Maintain Vendor and Material Master Data
- Perform Goods Receipt and Invoice Verification
- Learn standard SAP MM Transaction Codes

---

# 🏗 Purchase-to-Pay Workflow

```text
Vendor Master
      │
      ▼
Material Master
      │
      ▼
Purchase Requisition
      │
      ▼
Purchase Order
      │
      ▼
Goods Receipt
      │
      ▼
Invoice Verification
      │
      ▼
Payment Processing
```

---

# 📚 SAP MM Process

## 1️⃣ Vendor Master (BP)

Stores supplier information including:

- Vendor Name
- Address
- Contact Details
- Payment Terms
- Purchasing Information

---

## 2️⃣ Material Master (MM01)

Maintains information such as:

- Material Number
- Material Type
- Unit of Measure
- Storage Data
- Valuation Data

---

## 3️⃣ Purchase Requisition (ME51N)

Internal request created by departments to procure required materials.

Contains:

- Material
- Quantity
- Delivery Date
- Plant

---

## 4️⃣ Purchase Order (ME21N)

Official purchasing document sent to vendors.

Includes:

- Vendor
- Material
- Quantity
- Price
- Delivery Schedule
- Payment Terms

---

## 5️⃣ Goods Receipt (MIGO)

Confirms receipt of materials.

Functions:

- Updates Inventory
- Creates Material Document
- Records Stock Movement

---

## 6️⃣ Invoice Verification (MIRO)

Performs **Three-Way Matching** between:

- Purchase Order
- Goods Receipt
- Supplier Invoice

Ensures accurate invoice processing before payment.

---

## 7️⃣ Purchase Order Display (ME23N)

Displays complete Purchase Order information including:

- Vendor Details
- Material Details
- Delivery Status
- Document History

---

# 💻 SAP Transaction Codes

| Transaction Code | Description |
|------------------|-------------|
| **BP** | Business Partner (Vendor Creation) |
| **MM01** | Material Master |
| **ME51N** | Purchase Requisition |
| **ME21N** | Purchase Order |
| **MIGO** | Goods Receipt |
| **MIRO** | Invoice Verification |
| **ME23N** | Display Purchase Order |

---

# 📂 Repository Structure

```text
Purchase-Order-Management-System
│
├── Report
│   └── Purchase_Order_Management_System.pdf
│
├── Screenshots
│   ├── Vendor_Master.png
│   ├── Material_Master.png
│   ├── Purchase_Requisition.png
│   ├── Purchase_Order.png
│   ├── Goods_Receipt.png
│   ├── Invoice_Verification.png
│   └── Purchase_Order_Display.png
│
├── README.md
└── LICENSE
```

---

# 🚀 Features

- Vendor Master Management
- Material Master Management
- Purchase Requisition Creation
- Purchase Order Generation
- Goods Receipt Processing
- Invoice Verification
- Purchase Order Tracking
- Standard SAP MM Workflow

---

# ✅ Advantages

- Automates Procurement
- Improves Inventory Accuracy
- Reduces Manual Errors
- Centralized Business Data
- Better Vendor Management
- Faster Purchasing Process
- Improved Transparency
- Supports Enterprise Procurement

---

# ⚠ Limitations

- High Initial Implementation Cost
- Requires SAP Training
- Customization Needs Expertise
- Dependent on Accurate Master Data
- Licensing Costs

---

# 🔮 Future Enhancements

- Purchase Approval Workflow
- SAP FICO Integration
- Vendor Performance Dashboard
- SAP Analytics Reports
- Mobile Purchase Order Approval
- AI-Based Demand Forecasting

---

# 🛠 Technologies Used

- SAP S/4HANA
- SAP Materials Management (MM)
- Enterprise Resource Planning (ERP)

---

# 📖 Learning Outcomes

This project helped in understanding:

- SAP MM Fundamentals
- Procurement Lifecycle
- Purchase-to-Pay Process
- Vendor Management
- Inventory Management
- Invoice Verification
- ERP Business Processes
- Enterprise Procurement Automation



## ⭐ If you found this project useful, consider giving it a Star!
