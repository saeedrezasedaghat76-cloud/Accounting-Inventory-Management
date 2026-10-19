# Accounting & Inventory Management System

An integrated business management application developed with **C#, ASP.NET Core, Entity Framework Core, and SQL Server** to support accounting, sales and purchase invoices, payments, cheque management, inventory operations, and financial reporting.

The application brings essential business workflows together in one system, helping businesses organize financial records, review inventory movements, monitor cheque statuses, and analyze business performance.

**Project Focus:** Backend Development · Clean Architecture · CQRS · Business Logic · Data Access · Reporting

---

## Project Preview

![Financial Overview Dashboard](screenshots/financial-overview.png)

The dashboard provides an overview of key financial indicators and upcoming cheque information, helping users monitor business activity from a central location.

## Project Overview

### The Problem

Businesses need reliable ways to manage accounting records, invoices, payments, cheque obligations, and inventory. When these operations are difficult to review across separate workflows, maintaining organized records and monitoring business performance becomes more challenging.

### The Solution

This application provides a centralized environment for managing accounting and inventory operations, with dedicated workflows for financial documents, invoices, payments, cheques, product management, inventory reporting, and business analytics.

## Target Users

- **Business Owners & Managers:** Review financial performance, sales activity, and inventory indicators.
- **Accounting Staff:** Manage accounts, accounting documents, payments, receipts, and financial reports.
- **Sales & Purchasing Staff:** Create and manage sales and purchase invoices.
- **Inventory Staff:** Manage product records and review inventory movements and warehouse stock.

## Key Features

- **Accounting & Financial Documents:** Manage accounts, accounting documents, and account-related reports.
- **Sales & Purchase Invoices:** Create and manage invoices, review invoice details, and print invoices.
- **Payments & Receipts:** Manage financial transactions and expense-related payments.
- **Cheque Management:** Review cheque records, statuses, due dates, overdue cheques, and upcoming payments.
- **Product & Inventory Management:** Manage products and product groups, and review product, warehouse, and stock-movement reports.
- **Profit Reporting:** Review financial results by product, invoice, and date.
- **Dashboard Analytics:** Monitor sales and profit trends, top-selling products, low-inventory alerts, and upcoming cheques.
- **User & Role Management:** Manage user accounts, roles, role assignments, and role-associated claims.

## Technical Stack

| Technology | Purpose |
|---|---|
| C# | Backend logic and business operations |
| ASP.NET Core | Web application framework |
| Entity Framework Core | Data access and entity relationships |
| SQL Server | Relational data storage |
| ASP.NET Core Identity | User, role, and claims management |
| Clean Architecture | Separation of application responsibilities |
| CQRS | Organization of commands and queries |
| Docker | Containerization tooling |
| IIS | Application hosting and deployment |
| FastReport | Invoice printing |

## Architecture & Design

The solution is organized into four main projects:

- **Domain:** Core business entities and domain concepts.
- **Application:** Application operations organized around commands and queries.
- **Infrastructure:** Infrastructure concerns, including data access.
- **Presentation:** Application interface and presentation logic.

The project uses **Clean Architecture** to separate responsibilities and **CQRS** to organize application operations into commands and queries. This structure keeps application responsibilities organized and supports maintainability as the system evolves.

![Clean Architecture Solution](screenshots/clean-architecture-solution.png)

## Selected Application Screenshots

The following screenshots highlight seven selected areas of the application rather than documenting every page. Each example focuses on a practical business problem and the functionality provided to address it.

### 1. User & Role Permission Management

**Problem:** Different users need different levels of access to business operations.

**Solution:** ASP.NET Core Identity supports user and role management, role assignments, and role-associated claims.

**Business Value:** Provides a structured approach to user administration and permission configuration.

![User and Role Permission Management](screenshots/role-permission-management.png)

### 2. Product Management

**Problem:** Maintaining consistent product information becomes more difficult when records are not managed centrally.

**Solution:** The product management interface provides a centralized view for reviewing and managing product records.

**Business Value:** Makes product information easier to maintain and access during daily operations.

![Product Management](screenshots/product-management.png)

### 3. Inventory Movement Report

**Problem:** Understanding stock changes requires visibility into incoming and outgoing inventory activity.

**Solution:** The report presents inventory movements with information such as quantities, related invoices, dates, and warehouses.

**Business Value:** Helps users review inventory activity and investigate stock movements.

![Inventory Movement Report](screenshots/inventory-movement-report.png)

### 4. Sales Invoice Management

**Problem:** Sales operations require organized invoice records that can be reviewed and maintained.

**Solution:** The invoice workflow supports sales invoice creation, management, detail views, and printing.

**Business Value:** Keeps sales documentation accessible for related business workflows.

![Sales Invoice](screenshots/sales-invoice.png)

### 5. Sales & Inventory Analytics

**Problem:** Transaction records alone do not always make sales trends or inventory concerns easy to identify.

**Solution:** Dashboard analytics include sales and profit charts, top-selling products, and low-inventory alerts.

**Business Value:** Helps users monitor business performance and identify products that may require replenishment.

![Sales and Inventory Analytics](screenshots/sales-inventory-analytics.png)

## My Role & Contributions

I developed the application's backend and business functionality, working on:

- Application structure using Clean Architecture and CQRS.
- Data access and entity relationships.
- Accounting documents and account-related reporting.
- Sales and purchase invoice workflows.
- Payments, receipts, and cheque management.
- Product, inventory, and stock-movement reporting.
- Profit reports and dashboard data.
- User, role, and permission management.

## Deployment

The application was deployed on **IIS** for a transportation company affiliated with **NGHSCO**.

## Repository Notes

This repository serves as a project showcase, presenting the application's purpose, architecture, key features, and selected screenshots.

**The source code is not included in this public showcase.**

Only sanitized demonstration screenshots should be published. Confidential business information, real customer details, account records, credentials, and other sensitive data should not be exposed.

## Contact

- **GitHub:** [saeedrezasedaghat76-cloud](https://github.com/saeedrezasedaghat76-cloud)
- **LinkedIn:** [Add your LinkedIn profile URL]
- **Email:** [Add your professional email address]
