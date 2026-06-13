# Football Ticket Booking System

## Overview

This repository contains the database design and SQL query solutions for the **Football Ticket Booking System** assignment.

The project demonstrates:

- Entity Relationship Diagram (ERD) design
- Primary Key and Foreign Key relationships
- One-to-Many and Many-to-One relationships
- SQL table creation with constraints
- Data seeding
- SQL queries using filtering, pattern matching, joins, subqueries, aggregation, null handling, and pagination

---

## Database Schema

The system consists of three tables:

### Users

Stores platform users including football fans and ticket managers.

### Matches

Stores football match information, tournament categories, ticket prices, and match status.

### Bookings

Stores ticket booking records and connects users with matches through foreign key relationships.

---

## Entity Relationship Diagram (ERD)

Public ERD Link:

https://drive.google.com/file/d/1gk_BuD2sOxUejCBN1c_MLnPzmFRaIMpA/view?usp=sharing

The Draw.io source file is also included in this repository.

---

## SQL Features Used

- SELECT
- WHERE
- AND / OR
- LIKE / ILIKE
- COALESCE
- INNER JOIN
- LEFT JOIN
- Subqueries
- Aggregate Functions
- ORDER BY
- LIMIT
- OFFSET
- PRIMARY KEY
- FOREIGN KEY
- UNIQUE Constraint
- CHECK Constraint

---

## Repository Structure

```text
.
├── football-ticket-booking-system.drawio
├── QUERY.sql
└── README.md
```
