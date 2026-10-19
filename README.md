# Accounting & Inventory Management System

An integrated business management application designed for small and large businesses to manage accounting, financial transactions, sales and purchase invoices, payments, cheques, and inventory operations in one system.

The application helps businesses organize financial records, track inventory movements, manage day-to-day transactions, and monitor business performance through financial reports and dashboard analytics.

This project demonstrates my experience developing business-oriented applications using C#, ASP.NET Core, Entity Framework Core, and SQL Server.

## Target Users

The system is designed to support businesses of different sizes and operational needs, including:

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

The application follows Clean Architecture principles to separate business logic, application operations, infrastructure concerns, and presentation responsibilities. This structure helps organize the codebase, improve maintainability, and support future enhancements.

### Solution Structure and CQRS

The solution is organized into four projects: Domain, Application, Infrastructure, and Presentation. The Application layer uses commands and queries to organize supported operations, while the Infrastructure layer contains implementation details such as database access and Identity-related services.

This separation helps keep application responsibilities organized and provides a structured foundation for accounting, sales, and inventory functionality.

![Solution Structure and CQRS](screenshots/clean-architecture-solution.png)

Key design areas include:

- **Clean Architecture:** Separating application responsibilities into distinct layers.
- **CQRS:** Organizing supported operations into commands and queries.
- **Data Access:** Using Entity Framework Core to work with SQL Server.
- **Business Logic:** Supporting accounting, sales, inventory, cheque tracking, and financial reporting workflows.

## User & Role Permission Management

The application uses ASP.NET Core Identity to manage users, roles, and role-associated claims. Administrators can create roles, assign users to roles, and configure permissions associated with specific application operations.

### Role-Based Access Control

Role-based access control helps organize authorization rules for different groups of users. By assigning users to appropriate roles and associating permissions with those roles, the application can organize access to different areas and operations.

### Permission Management

The permission management interface allows administrators to add permissions to a role and remove existing permissions when access requirements change.

For example, the product-related permissions shown in the application include:

- **View Products:** Permission associated with accessing the product listing operation.
- **Add Products:** Permission associated with product creation.
- **Edit Products:** Permission associated with product editing.
- **Delete Products:** Permission associated with product deletion.

### Implementation

The backend uses `RoleManager<IdentityRole>` to create roles and manage role claims, while `UserManager<AppUser>` handles user creation and user-role assignments. Entity Framework Core integrates Identity entities with the application's database through `IdentityDbContext<AppUser>`.

This implementation separates user management, role assignment, and role-claim configuration, making authorization-related data easier to organize and maintain.

![Role Permission Management](screenshots/role-permission-management.png)

## Product & Inventory Management

### Product Management

The product management interface provides an overview of the product catalog, including product names, product groups, prices, and available management actions.

Centralizing product information helps organize inventory operations and provides a consistent reference for related business workflows, including sales and purchasing.

From a development perspective, this feature demonstrates the management of product data and its relationships with product groups and other business entities.

![Product Management](screenshots/product-management.png)

### Inventory Movement Report

The inventory movement report displays incoming and outgoing product quantities, related invoices, transaction dates, and warehouse information.

This report helps users review stock movements and trace inventory activity associated with business transactions. It also provides visibility into how product quantities change across inventory operations.

From a backend perspective, this feature demonstrates the presentation of inventory-related data and its relationships with products, invoice details, and warehouse accounts.

![Inventory Movement Report](screenshots/inventory-movement-report.png)

## Sales & Purchase Management

### Sales Invoice

The sales invoice interface demonstrates the workflow for creating and managing sales invoices.

Sales invoicing is a core business operation that connects product sales with customer transactions and related business records. The application also includes related accounting and inventory functionality to support broader business operations.

![Sales Invoice](screenshots/sales-invoice.png)

## Dashboard & Analytics

### Financial Overview

The financial dashboard provides a consolidated view of daily and monthly sales and profit, inventory totals, sales invoice counts, and upcoming cheque due dates.

By presenting these indicators in one place, the dashboard helps business users monitor key operational and financial information without navigating through individual sections.

From a development perspective, this feature demonstrates the presentation of summarized business data from accounting, sales, inventory, and cheque-related operations.

![Financial Overview](screenshots/financial-overview.png)

### Sales & Inventory Analytics

The analytics dashboard includes sales and profit charts for the last 30 days, top-selling products, and low-stock product monitoring.

These insights help users review sales trends, identify top-performing products, and recognize inventory items that may require replenishment.

The feature demonstrates how operational data can be summarized into visual reports to support business monitoring and decision-making.

![Sales and Inventory Analytics](screenshots/sales-inventory-analytics.png)

## Key Features

- **Sales & Purchase Management:** Manage sales and purchase invoices.
- **Accounting Operations:** Manage accounts, accounting documents, receipts, and payments.
- **Inventory Management:** Track product inventory and monitor low-stock items.
- **Cheque Management:** View cheque information and identify upcoming due dates.
- **Financial Reporting:** Review sales, profit, expenses, account details, and inventory-related reports.
- **Dashboard Analytics:** View key business indicators and sales and profit trends.
- **User & Role Management:** Manage users, assign roles, and configure role-associated claims.

## My Role

I developed the application's backend and business functionality, working with application architecture, data access, user and role management, accounting workflows, inventory operations, and dashboard reporting.

## Project Showcase

This repository presents selected screenshots and an overview of the project. The original application source code is not included.

## Contact

**Saeed Sedaghat**  
.NET Backend Developer

- [GitHub](https://github.com/saeedrezasedaghat76-cloud)
- [LinkedIn](https://www.linkedin.com/in/saeed-sedaghat)
- Email: sedaghatsaeedreza@yahoo.com
