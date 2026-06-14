# Football Ticket Booking System

## Overview

This repository contains the database design, ERD, SQL schema, sample data, query solutions, and theory question answers for the **Football Ticket Booking System** assignment.

The project demonstrates core relational database concepts including:

* Entity Relationship Diagram (ERD) design
* Primary Key and Foreign Key relationships
* Referential Integrity
* One-to-Many and Many-to-One relationships
* SQL table creation with constraints
* Data seeding
* SQL querying using joins, subqueries, filtering, null handling, and pagination

---

## Database Tables

The system consists of the following tables:

### Users

Stores football fans and ticket managers.

Fields:

* user_id
* full_name
* email
* role
* phone_number

### Matches

Stores football match information and ticket details.

Fields:

* match_id
* fixture
* tournament_category
* base_ticket_price
* match_status

### Bookings

Stores ticket purchase records and connects users with matches.

Fields:

* booking_id
* user_id
* match_id
* seat_number
* payment_status
* total_cost

---

## Relationships

* One User → Many Bookings
* One Match → Many Bookings
* Each Booking belongs to exactly one User and one Match

---

## Entity Relationship Diagram (ERD)

Public ERD Link:

https://drive.google.com/file/d/1gk_BuD2sOxUejCBN1c_MLnPzmFRaIMpA/view

The ERD was created using Draw.io and the source file is included in this repository.

---

## Theory Question Answers

Public Video Link:

https://drive.google.com/file/d/1izXdsW8dbna4EvXCICkw_u-SFTPKOgyP/view

Questions Answered:

1. Foreign Key and Referential Integrity
2. COUNT() and HAVING
3. Primary Key and NULL Values

---

## SQL Queries

All schema definitions, sample data, and assignment queries are available in:

```text
QUERY.sql
```

Queries included:

1. Filtering Champions League matches
2. Pattern matching using ILIKE
3. NULL handling using COALESCE
4. INNER JOIN
5. LEFT JOIN
6. Subquery with AVG()
7. Pagination using LIMIT and OFFSET

---

## SQL Concepts Used

* SELECT
* WHERE
* AND / OR
* ILIKE
* COALESCE
* INNER JOIN
* LEFT JOIN
* Subqueries
* Aggregate Functions
* ORDER BY
* LIMIT
* OFFSET
* PRIMARY KEY
* FOREIGN KEY
* UNIQUE Constraint
* CHECK Constraint

---

## Technologies Used

* PostgreSQL
* SQL
* Draw.io
* Git
* GitHub

---

## Repository Structure

```text
.
├── QUERY.sql
├── README.md
└── football-ticket-booking-system.drawio
```
