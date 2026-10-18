# Accounting & Inventory Management System

An integrated business management application designed for small and large businesses to manage their accounting, financial transactions, sales and purchase invoices, payments, cheques, and inventory operations in one system.

The application helps businesses organize financial records, track inventory movements, manage day-to-day transactions, and monitor business performance through financial reports and dashboard analytics.

This project demonstrates my experience developing business-oriented applications using C#, ASP.NET Core, Entity Framework Core, and SQL Server.

## Target Users

The system is designed to support different business sizes and operational needs, including:

- **Business Owners and Managers:** Monitoring financial performance, sales, and inventory status.
- **Accounting Staff:** Managing accounts, financial transactions, receipts, payments, and accounting documents.
- **Sales and Purchasing Staff:** Managing sales and purchase invoices.
- **Inventory Staff:** Managing products, tracking stock movements, and monitoring inventory levels.

## Technical Stack

- **Language:** C#
- **Backend Framework:** ASP.NET Core
- **Data Access:** Entity Framework Core
- **Database:** Microsoft SQL Server
- **Authentication & Authorization:** ASP.NET Core Identity
- **Architecture:** Clean Architecture and CQRS

## Architecture & Design

The application is organized around business operations, with a focus on separation of concerns, maintainability, and reliable data management.

### Solution Structure and CQRS

The solution is organized into four projects: Domain, Application, Infrastructure, and Presentation. The Application layer uses commands and queries to organize supported operations and maintain separation of concerns.

![Solution Structure and CQRS](screenshots/clean-architecture-solution.png)

Key design areas include:

- **Clean Architecture:** Separating application responsibilities into distinct layers.
- **CQRS:** Organizing supported operations into commands and queries.
- **Data Access:** Using Entity Framework Core to work with SQL Server.
- **Business Logic:** Supporting accounting, sales, inventory, cheque tracking, and financial reporting workflows.

## Product & Inventory Management

### Product Management

This screen displays the product catalog, including product names, product groups, prices, and product management actions.

![Product Management](screenshots/product-management.png)

### Inventory Movement Report

This report tracks incoming and outgoing product quantities, related invoices, transaction dates, and warehouse information.

![Inventory Movement Report](screenshots/inventory-movement-report.png)

## Sales & Purchase Management

### Sales & Purchase Invoice

The sales invoice screen demonstrates the workflow for creating and managing sales invoices.

![Sales Invoice](screenshots/sales-invoice.png)

## Dashboard & Analytics

### Financial Overview

The dashboard provides a consolidated view of daily and monthly sales and profit, inventory totals, sales invoice counts, and upcoming cheque due dates.

![Financial Overview](screenshots/financial-overview.png)

### Sales & Inventory Analytics

The dashboard includes sales and profit charts for the last 30 days, top-selling products, and low-stock product monitoring.

![Sales and Inventory Analytics](screenshots/sales-inventory-analytics.png)

## Key Features

- **Sales & Purchase Management:** Manage sales and purchase invoices.
- **Accounting Operations:** Manage accounts, accounting documents, receipts, and payments.
- **Inventory Management:** Track product inventory and monitor low-stock items.
- **Cheque Management:** View cheque information and identify upcoming due dates.
- **Financial Reporting:** Review sales, profit, expenses, account details, and inventory-related reports.
- **Dashboard Analytics:** View key business indicators and sales and profit trends.

## My Role

I developed the application's backend and business functionality, working with application architecture, data access, accounting workflows, inventory operations, and dashboard reporting.

## Project Showcase

This repository presents selected screenshots and an overview of the project. The original application source code is not included.

## Contact

**Saeed Sedaghat**  
.NET Backend Developer

- [GitHub](https://github.com/saeedrezasedaghat76-cloud)
- [LinkedIn](https://www.linkedin.com/in/saeed-sedaghat)
- Email: sedaghatsaeedreza@yahoo.com
