# Target Brazil E-Commerce Database Project

A database design and SQL analytics project built from the Target Brazil e-commerce dataset. This project models core business operations through an ER diagram and relational schema, then uses SQL-based analysis to generate insights related to sales, fulfillment, customer behavior, and business performance.

## Project Overview

The goal of this project was to design a structured database that could support decision-making for a large e-commerce business. Using the Target Brazil dataset, the project identifies key entities, defines relationships, normalizes the schema, and applies SQL queries to answer business questions.

The project focuses on:
- conceptual database design
- logical schema development
- normalization into 3NF
- SQL querying for managerial insights
- recommendations for improved data collection

## Business Problem

Target Brazil’s e-commerce operations generate data across customers, orders, payments, sellers, products, reviews, and deliveries. Without a well-structured relational database, it becomes difficult to track operational performance, understand customer satisfaction, and support analytics at scale.

This project addresses that challenge by creating a database design that improves data organization and enables meaningful business analysis.

## Dataset

**Source:** Target (Olist) Brazilian E-Commerce Dataset from Kaggle

**Link:** https://www.kaggle.com/datasets/ujjwalinsights/target-case-study-using-sql

The dataset includes information on:
- customers
- orders
- order items
- payments
- products
- sellers
- reviews
- geolocation
- order delivery timestamps

## Objectives

- Design an ER diagram with entities and meaningful business relationships
- Convert the conceptual model into a logical relational schema
- Identify primary keys and foreign keys
- Normalize the database into Third Normal Form (3NF)
- Write SQL queries to answer business and managerial questions
- Recommend additional attributes or data collection improvements for stronger analytics

## Entity Design

The database design centers around major operational entities such as:

- **Customers**
- **Orders**
- **Order Items**
- **Payments**
- **Products**
- **Sellers**
- **Reviews**

Each entity was designed with relevant attributes and connected through business relationships such as:
- customers place orders
- orders contain order items
- order items reference products
- sellers fulfill products
- orders receive payments
- orders receive reviews

## Database Design Process

### 1. Conceptual Model
Created an ER diagram to capture the major entities, their attributes, and cardinality relationships across the business.

### 2. Logical Model
Converted the ERD into a relational schema with clearly defined:
- primary keys
- foreign keys
- one-to-many relationships
- associative structures where needed

### 3. Normalization
Reviewed the schema for redundancy and dependency issues, then refined tables to satisfy **Third Normal Form (3NF)**.

### 4. SQL Analytics
Wrote SQL queries to generate business insights from the data, such as:
- sales trends
- delivery performance
- customer review patterns
- seller activity
- payment behavior

## Example Business Questions

Some of the questions explored in this project include:

- Which products or sellers drive the highest sales?
- How does delivery speed affect customer satisfaction?
- What payment methods are used most often?
- Which customer segments generate the most value?
- Are there patterns in low-rated reviews tied to shipping delays or product categories?

## Key Insights

Examples of insights supported by this project include:
- identifying performance differences across sellers
- measuring relationships between delivery timing and review scores
- understanding payment preferences across orders
- highlighting areas where better customer or marketing data would improve analytics

## Recommended Data Improvements

To make the database more valuable for future analytics, several additional attributes or tracking fields could be added, such as:
- customer segment
- acquisition channel
- campaign source
- delivery exception reason
- repeat purchase indicator
- customer lifetime value metrics

These additions would improve analysis in marketing, retention, and operational optimization.

## Tools Used

- **SQL**
- **ER modeling / database design**
- **Normalization (3NF)**
- **Kaggle dataset**
- **Relational database concepts**

## Project Deliverables

- ER Diagram
- Relational Schema
- Dependency Analysis
- 3NF Conversion
- SQL Queries
- Business Insight Summary

## Skills Demonstrated

- Database design
- Entity-relationship modeling
- Relational schema development
- Data normalization
- SQL querying
- Business analysis
- Translating raw data into managerial insights

## Possible Future Enhancements

- Build a dashboard for KPI tracking
- Add customer segmentation features
- Extend the schema with marketing attribution data
- Create views and stored procedures for recurring analytics
- Use Python or Tableau for visual reporting on top of the SQL outputs



This project is for academic and portfolio use.
