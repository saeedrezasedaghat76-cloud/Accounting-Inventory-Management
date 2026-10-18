# Accounting & Inventory Management System

A web-based business application for managing accounting operations, sales and purchase invoices, inventory, payments, cheques, and financial reporting.

This project demonstrates my experience developing business-oriented applications using C#, ASP.NET Core, Entity Framework Core, and SQL Server.

## Dashboard & Analytics

### Financial Overview

The dashboard provides a consolidated view of daily and monthly sales and profit, inventory totals, sales invoice counts, and upcoming cheque due dates.

![Financial Overview](screenshots/financial-overview.png)

### Sales & Inventory Analytics

The dashboard includes sales and profit charts for the last 30 days, top-selling products, and low-stock product monitoring.

![Sales and Inventory Analytics](screenshots/sales-inventory-analytics.png)

## Sales & Purchase Management

### Sales Invoice

The sales invoice screen demonstrates the workflow for creating and managing sales invoices.

![Sales Invoice](screenshots/Sales Invoice.png)

## Key Features

- **Sales & Purchase Management:** Manage sales and purchase invoices.
- **Accounting Operations:** Manage accounts, accounting documents, receipts, and payments.
- **Inventory Management:** Track product inventory and monitor low-stock items.
- **Cheque Management:** View cheque information and identify upcoming due dates.
- **Financial Reporting:** Review sales, profit, expenses, account details, and inventory-related reports.
- **Dashboard Analytics:** View key business indicators and sales and profit trends.

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
