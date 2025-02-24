---
title: "Dream Homes NYC"
description: "Dream Homes NYC is a real estate agency servicing the Tri-State area (NY, NJ, CT). They connect home sellers with potential buyers and homeowners with renters. The company aims to modernize its systems and build a database for organizing corporate data, client transactions, properties, and agent operations.

The objective is to create a robust database that improves efficiency, supports future analytics, and integrates with potential app development."
date: 2024-08-05T12:00:00+08:00
tags: ["SQL", "Python", "Data Visualization", "css", "ETL", "MongoDB", "Metabase"]
draft: false
---

## Functional Requirements
### Client and Property Management
- **Client Information**: Store buyer, seller, and renter details, including preferences and transaction history.
- **Property Listings**: Maintain property details (location, size, price, availability status).
- **Transactions**: Track all property transactions, including price, commission, and transaction phases.

### Operational Efficiency
- **Events**: Manage open houses, client appointments, and agent schedules.
- **Communications**: Store all client communications (emails, calls, messages).

### Business Data Management
- **Office Locations**: Track office details (address, contact info, manager).
- **Employees**: Maintain employee records, employment status, and performance metrics.
- **Financial Data**: Monitor company expenses, profits, and office-specific performance.

### Insights and Analytics
- **Reporting**: Generate financial and operational reports for decision-making.
- **Analytics**: Create dashboards for market trends, agent performance, and client behaviors.

---

## Non-Functional Requirements
- **Scalability**: Support growing data from multiple offices and transactions.
- **Security**: Ensure robust security for client and corporate data.
- **Compliance**: Adhere to real estate regulations and data protection laws.
- **Cloud Storage**: Implement cloud-based solutions for reliability and future app development.
- **Data Backup**: Establish automated data backup procedures.

---

## Proposal
We propose a structured database focusing on rental and purchase transactions to enhance Dream Homes NYC's operations and data management.

### **Preliminary Solution Ideas**
#### **Core Tables**
- **Offices**: Office details including location and managers.
- **Employees**: Employee information (roles, assignments, employment status).
- **Properties**: Property details (type, price, status).
- **Clients**: Client contact details and preferences.
- **Transactions**: Records of rentals and purchases.
- **Events**: Tracks open houses and appointments.

#### **Supporting Tables**
- **Addresses**: Store location data for marketing and reporting.
- **Property Types**: Classifies properties (apartments, townhouses, single-family homes).
- **Agents**: Defines agent roles.
- **Transaction Types**: Differentiates rental and purchase transactions.
- **Business Expenses**: Tracks expenses for financial reporting.

---

## Team Structure and Timeline

### **Project Work Plan**
| Milestone | Due Date | Client Review | Deliverables | Owner(s) |
|-----------|---------|---------------|--------------|---------|
| **Checkpoint 1** - Documenting Business Requirements | Jul 14, 2024 | Jul 16, 2024 | Requirement List | Full Team |
| **Checkpoint 2** - Schema Design | Jul 21, 2024 | Jul 23, 2024 | ER Diagram, SQL Code | Rachel (SQL), Valerie (ER Diagram) |
| **Checkpoint 3** - ETL Implementation | Jul 28, 2024 | Jul 30, 2024 | Sample Data, Python Scripts | Bryon |
| **Checkpoint 4** - UX Development | Aug 4, 2024 | Aug 6, 2024 | SQL Queries, Reports, KPIs | Rachel (Queries), Valerie (Reports), Bryon (Dashboards) |

---

## **Database Design**
### **Schema Overview**
The schema includes tables for managing property transactions, clients, employees, and financial records. The design ensures scalability and compliance with industry standards.

### **Triggers and Integrity Constraints**
- **Agent Sales Tracking**: Auto-updates total agent sales.
- **Property Status Management**: Automatically adjusts status upon transaction completion.

---

## **Extract, Transform, Load (ETL) Strategy**
### **Data Creation and Import**
- **Python scripts** generate realistic test data.
- **SQL** is used for data import and transformation.

### **Denormalized Data Files**
| File | Description |
|------|-------------|
| offices.csv | Office locations with managers and contacts |
| clients.csv | Client details with transaction history |
| employees.csv | Employee records and roles |
| properties.csv | Listings with property details |
| transactions.csv | Records of completed sales and rentals |

---

## **Analytics Applications**
### **Extracting Insights**
- SQL queries track active properties, agent commissions, and transaction trends.

### **Reporting and Dashboards**
- **Financial Reports**: Revenue breakdown (sales, rentals, commissions).
- **Agent Performance**: Sales rankings, client interactions.
- **Market Trends**: Neighborhood-based pricing trends.
- **Client Engagement**: Frequency and types of client interactions.

---

## **Future Development Opportunities**
- **Mobile Application**: Integrate real-time access for agents and clients.
- **AI and Predictive Analytics**: Forecast market trends and client preferences.
- **Automated Marketing Tools**: Personalized client outreach.

---

## **Conclusion**
The Dream Homes NYC database enhances real estate operations through structured data management, reporting, and analytics. Future developments will focus on expanding functionality, automation, and user engagement to optimize business outcomes.

---

