
***

# 🧴 Modernizing Bioskin Inventory Management
**Transitioning from Google Sheets to an Integrated IMS**

![Project Status](https://img.shields.io/badge/Status-In%20Development-orange)
![Client](https://img.shields.io/badge/Client-Bioskin%20PH-blue)
![Course](https://img.shields.io/badge/Course-CS229-green)

## 📄 Executive Summary
This project is a centralized **Inventory Management System (IMS)** designed for **Bioskin PH**, a skincare manufacturing and retail business based in Davao City.

Currently, Bioskin relies on manual data entry via Google Sheets to track inventory across their physical store and e-commerce platforms (Shopee, Lazada, TikTok). This project aims to replace that manual workflow with a cloud-based solution that automates stock tracking, minimizes human error, and provides real-time analytics for decision-making.

---

## 🧐 The Problem
Despite having a high volume of products (200-300 SKUs) and utilizing systems like SAP (for accounting) and a standalone POS, Bioskin PH faces several operational bottlenecks:
*   **Manual Inventory Tracking:** Stock levels are updated manually on Google Sheets, leading to delays and discrepancies.
*   **Lack of Synchronization:** Sales from the physical store and e-commerce platforms are not automatically deducted from the master inventory.
*   **No Real-Time Visibility:** Management lacks instant access to low-stock alerts or sales performance, making restocking inefficient.
*   **Human Error:** The reconciliation process between the POS, SAP, and physical stock is prone to encoding errors.

## 💡 The Solution
We are developing a **Customized Inventory Management System (IMS)** that serves as the "Single Source of Truth" for Bioskin's stock.

### Key Objectives:
1.  **Centralization:** Unify inventory tracking for both retail and warehouse operations.
2.  **Automation:** Automatically deduct stock upon transaction entry, reducing manual reconciliation.
3.  **Reporting:** Generate automated daily, monthly, and quarterly reports for sales and inventory status.

---

## ✨ Key Features (User Requirements)
*   **Dashboard:** A visual overview of total stock, low stock alerts, and daily sales.
*   **Product Management:** database for 300+ SKUs, including product names, sizes, barcodes, and pricing.
*   **Real-Time Stock Updates:** Instant inventory deduction when a sale is recorded.
*   **Reporting Module:** Automated generation of inventory movement and sales performance reports.
*   **Cloud Synchronization:** Operates with cloud storage to ensure data accessibility across authorized devices.
*   **Security:** Role-based access control (Admin keys) to protect sensitive data.

---

## 🛠️ Tech Stack
*(Note: Update this section based on the specific technologies you decided to use in Chapter 3)*

*   **Frontend:** [e.g., React / Vue / Blade Templates]
*   **Backend:** [e.g., PHP Laravel / Node.js]
*   **Database:** [e.g., MySQL / PostgreSQL]
*   **Cloud/Hosting:** [e.g., Google Cloud / AWS / Hostinger]

---

## 📸 Screenshots

| Login Screen | Dashboard |
| :---: | :---: |
| ![Login Screen](https://github.com/user-attachments/assets/3259475b-6f54-4da3-9a54-e9f7587ea5b1) | ![Dashboard](https://github.com/user-attachments/assets/9738c219-91fb-435c-84e7-ff1502cd3c73) |

| Inventory List | Reporting |
| :---: | :---: |
| ![Inventory List](https://github.com/user-attachments/assets/9c649667-db19-49cf-a3c0-8e7a2a77808f) | ![Reporting](https://github.com/user-attachments/assets/ef02e992-26bc-4712-a538-936a88073f3b) |

---

## 👥 The Team
**College of Information and Computing**  
*University of Southeastern Philippines (USeP)*

*   **Boladola, Jaylord Jan A.** - *[Role, e.g., Developer]*
*   **Ga-as, James O.** - *[Role, e.g., Project Manager/Interviewer]*
*   **Go, John Aaron L.** - *[Role, e.g., Analyst]*
*   **Supnet, John Benedict P.** - *[Role, e.g., Developer/Designer]*

---

## 📂 Project Structure
```text
├── docs/                  # Documentation (Interview transcripts, Proposal PDF)
├── src/                   # Source code
├── database/              # SQL dumps and migrations
├── public/                # Assets (Images, CSS, JS)
└── README.md              # Project Overview
```

---

### 📝 Acknowledgments
We would like to thank **Ms. Tammy Castañares**, **Ms. Fahmia Basari**, and the staff of **Bioskin PH** for their time and valuable insights during the data gathering phase.

*In Partial Fulfillment of the Requirements in CS229 - Design and Development Methodologies, 2nd Semester, SY 2024-2025.*
