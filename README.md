# Invoice & Product Management System (SQL) 🧾

A robust relational database designed to manage the core operations of a commercial supply chain. This project models the complete flow from suppliers and product inventory to customer invoicing and line-item tracking.

[Image of an entity-relationship diagram for an invoice and product management system]

### 🚀 Key Technical Features

* **Relational Mapping (DDL)**: Implements a multi-table architecture using `PRIMARY KEY` and `FOREIGN KEY` constraints to ensure data consistency between suppliers, products, and invoices.
* **Transactional Integrity**: Features a specialized `Item` table to handle many-to-many relationships between invoices and products, tracking unit prices and quantities per transaction.
* **Business Entity Logic**: Segregates data into logical domains (Customers, Suppliers, Products, and Invoices) to minimize redundancy and support scalable queries.
* **Status Tracking**: Integrated status management for suppliers to monitor active partnerships and supply chain availability.

### 🛠 SQL Operations (CRUD)
The system is fully equipped with scripts to perform:
- **Data Insertion (DML)**: Seamlessly onboarding new customers, suppliers, and product catalogs.
- **Relational Querying (DQL)**: Generating detailed invoice reports by joining customer profiles with transactional line items.
- **Inventory Management**: Tracking product cost prices and supplier associations.

### 💻 Tech Stack
- **Database Engine:** SQLite
- **Languages:** SQL (DDL, DML, DQL)
- **Domain:** Inventory Management, Invoicing Systems, Relational Modeling.

---
*Note: This project showcases my proficiency in relational database architecture for commercial applications. I am currently scaling these SQL foundations into Go (Golang) back-end services with PostgreSQL and Docker.*
