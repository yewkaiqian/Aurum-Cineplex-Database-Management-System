# Aurum Cineplex – Cinema Database Management System

## Overview

The Cinema Database Management System (CDMS) is a Microsoft Access-based relational database application designed to support the daily operations of Aurum Cineplex, a simulated medium-sized cinema operator.

The system centralises movie information, screening schedules, ticket bookings, customer records, seat assignments, payment records and staff scheduling. It incorporates interactive forms, SQL queries, management reports and a graphical switchboard interface to facilitate data entry, information retrieval and operational decision-making.

## Key Features

- **Movie Management** – Maintain movie titles, genres, durations, ratings, release dates and screening statuses.
- **Screening Management** – Manage movie screening dates, times and hall assignments.
- **Hall and Seat Management** – Maintain cinema hall information, seating capacities and seat categories.
- **Customer Management** – Register customers and maintain loyalty membership records.
- **Ticket Booking** – Manage customer bookings, ticket records and seat assignments.
- **Payment Management** – Record payment methods, transaction amounts and loyalty discounts.
- **Staff Management** – Maintain staff information, shift schedules and hall assignments.
- **Management Reporting** – Generate reports on ticket sales, customer booking activity and cinema hall schedules.
- **Graphical Switchboard** – Access database tables, queries, forms and reports through a centralised navigation interface.

## Technologies Used

| Technology | Purpose |
|---|---|
| Microsoft Access | Relational database and application development |
| SQL | Data retrieval, filtering and analysis |
| Microsoft Access Forms | Interactive data entry interfaces |
| Microsoft Access Reports | Business reporting and data presentation |
| ERD | Database structure and relationship modelling |

## Database Design

The system consists of 11 interrelated database tables:

| Table | Purpose |
|---|---|
| Movie | Movie information |
| Hall | Cinema hall information |
| Screening | Movie screening schedules |
| Customer | Customer and loyalty membership records |
| Booking | Customer reservation records |
| Payment | Payment transaction records |
| Ticket | Individual ticket information |
| Seat | Cinema seat information |
| Staff | Employee records |
| Shift | Employee shift schedules |
| StaffShift | Staff, shift and hall assignments |

The database incorporates primary keys, foreign keys, composite keys and relational integrity constraints to maintain structured and consistent records.

## Database Queries

| Query | Purpose |
|---|---|
| Customer Booking Query | Retrieve bookings made by a specified customer |
| Upcoming IMAX Screenings | Retrieve upcoming screenings held in IMAX halls |
| Staff Shift Query | Retrieve employee shift information |

## Interactive Forms

- **Ticket Booking Form** – Manage booking details and associated ticket records through a form and subform.
- **Movie Entry Form** – Enter and maintain movie information.
- **Customer Registration Form** – Register customers and maintain customer records.

## Management Reports

- Monthly ticket sales by movie
- Customers who booked more than five tickets in a month
- Cinema daily hall schedule

## User Interface

The application includes five switchboard interfaces:

- Main Switchboard
- Table Records Switchboard
- Query Switchboard
- Form Switchboard
- Report Switchboard

These interfaces provide organised access to database objects without requiring users to navigate the underlying database structure manually.

## Technical Implementation

- Relational database design
- Entity-Relationship modelling
- Primary, foreign and composite keys
- Referential integrity
- SQL joins and conditional filtering
- Data entry forms and subforms
- Database reporting
- Graphical interface design
- Business rules and requirements analysis
- Data dictionary development

## Repository Structure

| File | Description |
|---|---|
| `Cinema Project.accdb` | Microsoft Access database application containing tables, queries, forms and reports |
| `Report.pdf` | Detailed project documentation, ERD, business rules, data dictionary and application screenshots |

## Getting Started

### Prerequisites

- Microsoft Access with support for the ACCDB file format

### Execution

1. Clone or download this repository.
2. Open `Cinema Project.accdb` using Microsoft Access.
3. Navigate through the main switchboard to access database tables, queries, forms and reports.
4. Explore the sample records and available database functionalities.

## Contributors

- Lee Zi Qian
- Liew Jia Min
- Ooi Jun Kai
- Yew Kai Qian

## Project Documentation

Refer to the [Project Report](Report.pdf) for detailed documentation, including:

- Project background and objectives
- Entity-Relationship Diagram (ERD)
- Business rules and assumptions
- Data dictionary and sample records
- SQL queries and explanations
- Form and report designs
- Switchboard interfaces
- System limitations and future improvements

## Project Background

This project was developed collaboratively by four undergraduate students at Universiti Tunku Abdul Rahman (UTAR) as part of the Database Development and Applications coursework.

- **Course:** UCCD1203 – Database Development and Applications
- **Trimester:** June 2025
- **Project Type:** Academic Group Project
- **Platform:** Microsoft Access

## Project Scope

This project is an academic prototype demonstrating the practical application of relational database design, SQL, graphical database interfaces and business reporting within a simulated cinema environment.
