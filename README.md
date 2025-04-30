# 🌐 SIA Web

## 🧭 Overview
**SIA Web** is a planned web-based extension of the SIA (Sistema Integral de Abastecimientos) platform at AHMSA. The goal of this system was to centralize multiple procurement and material management modules under one scalable, modern, and accessible platform using web technologies.

While the original SIA was a Windows Forms application, **SIA Web** was designed to be its cross-platform successor, ensuring users could interact with procurement tools from any device or location securely.

## 💡 Idea & Concept
SIA Web was envisioned to:
- Unify various departmental workflows (Purchasing, Warehouse, Projects)
- Enable real-time access to purchase approvals, petty cash requests, material tests
- Offer dashboards, alerts, and KPIs to decision-makers
- Reduce reliance on desktop-bound systems and encourage mobility

## ✨ Features & Functionality (Planned or Proposed)
- 🧾 Purchase Request Management (incl. petty cash & materials)
- 🔎 Vendor and product database search
- 📥 Digital document uploads (quotes, invoices, evidence)
- 💬 Notifications and reminders
- 🧩 Module Integration: Petty Cash, Material Testing, Contracts, Estimations
- 📊 Dashboard for KPIs and workflow summaries
- 🌐 Multi-role login with permissions per department

## ⚙️ Tech Stack (Planned)
- **Frontend:** HTML, CSS, JavaScript (React or Razor Pages)
- **Backend:** ASP.NET Core
- **Database:** SQL Server (shared with legacy SIA)
- **Authentication:** Role-based with Microsoft Identity or Azure AD (planned)
- **IDE:** Visual Studio

## 🏗 Architecture & Design
- Modular design to support multi-department expansion
- Cloud-hostable ASP.NET Core backend
- Role-based access control and session logging
- Integrated with legacy SIA DB structure

## 🚀 Installation & Setup
- **Hosting:** Company intranet or Azure App Services
- **Access:** Authenticated employees based on role
- **Requirements:** Secure HTTPS and endpoint authorization

> **Note:** As of 2025, some features remain under prototype or proposal status.

## 🧑‍💻 My Role & Contributions
- 💡 Proposed architecture and tech stack for SIA Web
- 🔄 Migrated initial data models and logic from WinForms version
- 📋 Designed prototype UI for dashboards and modules
- 💬 Collaborated with users to identify critical UX needs

## 🧗 Challenges & Learnings
- Planned DB reuse while preserving transactional integrity
- Cross-department feature alignment for multi-module cohesion
- UX redesign for responsive and mobile-friendly operation

## 📈 Future Enhancements
- Build fully responsive UI with multi-tenant support
- Integrate Power BI for reporting and forecasting
- Enable mobile workflows for warehouse and field engineers

## 🪪 License
⚠️ **Internal Use Only**  
Originally under MIT License. Changed to **CC BY-NC-ND 4.0** as of April 22, 2025.

## 🔗 Related Projects
- **[SIA](https://github.com/HermiloOrtega/SIA)**
- **[SIA – Petty Cash Module](https://github.com/HermiloOrtega/SIA-Petty-Cash)**
- **[SIA – Material Testing Module](https://github.com/HermiloOrtega/SIA-Material-Testing)**