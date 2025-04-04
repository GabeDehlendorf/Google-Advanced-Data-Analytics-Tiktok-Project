# TikTok Claims Classification Project

## Overview
This project simulates the work of a data professional working at TikTok tasked with creating a machine learning algorithm that will sort tiktoks into claims of fact or opinions.
The company would like to streamline the process of content review since millions of tiktoks are reported monthly.
The project's labs and executive summaries took place at the end of every module in the course, integrating the newly learned data analysis techniques into the next sequential step of the whole process.

## Key Components

* Executive Summaries 
* `diagrams/`: Contains the Entity-Relationship Diagram (ERD) in draw.io format (`ecommerce_erd.drawio`).
* `schema/`: Includes the SQL DDL script for creating the database schema in PostgreSQL (`ecommerce_schema.sql`).
* `documentation/`: Contains a data dictionary in CSV format (`data_dictionary.csv`).
* `sample_data/`: Includes a small, anonymized CSV file with sample customer data (`sample_customers.csv`).

## Technologies Used

* Data Modeling Tool: draw.io
* Database: PostgreSQL
* Diagram Format: draw.io XML
* Schema Definition Language: SQL

## Data Sources

This data model is based on hypothetical transactional data generated from an e-commerce platform. The primary data categories include customer information, product details, order history, and payment records.

## Data Model Details

The core entities in this model are:

* **Customers:** Stores information about registered users.
* **Products:** Contains details about the items available for sale.
* **Orders:** Represents customer purchase transactions.
* **Order_Items:** Links orders to specific products and quantities.
* **Payments:** Records payment information for orders.

Relationships between these entities are defined in the ERD. For example, a Customer can have multiple Orders (one-to-many relationship).

## How to Understand/Use the Project

1.  **View the Diagram:** Open the `ecommerce_erd.drawio` file in draw.io (or import the XML into the online editor).
2.  **Implement the Schema:** Execute the `ecommerce_schema.sql` script against a PostgreSQL database to create the tables.
3.  **Understand the Data:** Refer to the `data_dictionary.csv` file for descriptions of each table and column.
4.  **Explore Sample Data:** The `sample_customers.csv` file provides example data for the `Customers` table.

## Assumptions and Constraints

* This model represents a simplified version of an e-commerce platform and may not include all possible features (e.g., shipping details, product reviews).
* Data types in the schema are based on common PostgreSQL conventions.

## Future Enhancements

* Adding entities for shipping information and tracking.
* Implementing a more detailed product catalog with categories and attributes.

## Author

[Your Name/GitHub Username] (optional)
