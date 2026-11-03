# ER Diagram Workshop – Submission Template

## Objective
To understand and apply ER modeling concepts by creating ER diagrams for real-world applications.

## Purpose
Gain hands-on experience in designing ER diagrams that represent database structure including entities, relationships, attributes, and constraints.

---

# Scenario A: City Fitness Club Management

**Business Context:**  
FlexiFit Gym wants a database to manage its members, trainers, and fitness programs.

**Requirements:**  
- Members register with name, membership type, and start date.  
- Each member can join multiple programs (Yoga, Zumba, Weight Training).  
- Trainers assigned to programs; a program may have multiple trainers.  
- Members may book personal training sessions with trainers.  
- Attendance recorded for each session.  
- Payments tracked for memberships and sessions.

### ER Diagram:
<img width="795" height="700" alt="image" src="https://github.com/user-attachments/assets/8150498f-ae95-445c-a5c7-c62fd0e91b3c" />

### Entities and Attributes
<img width="431" height="234" alt="image" src="https://github.com/user-attachments/assets/89053492-295b-42b5-be94-165a90ed88ab" />


### Relationships and Constraints
<img width="402" height="208" alt="image" src="https://github.com/user-attachments/assets/2310fde3-cf70-4076-9385-abab10351335" />


### Assumptions
- Each member has a unique Member_ID.
- A member can enroll in multiple programs.
= Attendance is recorded for every session attended.
- Members can make multiple payments.
- Members can book personal trainers.
---

# Scenario B: City Library Event & Book Lending System

**Business Context:**  
The Central Library wants to manage book lending and cultural events.

**Requirements:**  
- Members borrow books, with loan and return dates tracked.  
- Each book has title, author, and category.  
- Library organizes events; members can register.  
- Each event has one or more speakers/authors.  
- Rooms are booked for events and study.  
- Overdue fines apply for late returns.

### ER Diagram:
<img width="777" height="670" alt="image" src="https://github.com/user-attachments/assets/681c4d3c-c581-4dc1-b599-282bd9dfa765" />


### Entities and Attributes
<img width="428" height="242" alt="image" src="https://github.com/user-attachments/assets/04911298-abf1-4a2a-a9b5-878b86bf9306" />


### Relationships and Constraints
<img width="412" height="206" alt="image" src="https://github.com/user-attachments/assets/c283df74-0247-4d0e-a486-fbf731af5e90" />


### Assumptions
- Each member has a unique Member_ID.
- Members can borrow multiple books.
- Overdue book returns may generate fines.
- Members can register for multiple events.
- Each event has one or more speakers.
- Rooms can be booked for events or study purposes.
---

# Scenario C: Restaurant Table Reservation & Ordering

**Business Context:**  
A popular restaurant wants to manage reservations, orders, and billing.

**Requirements:**  
- Customers can reserve tables or walk in.  
- Each reservation includes date, time, and number of guests.  
- Customers place food orders linked to reservations.  
- Each order contains multiple dishes; dishes belong to categories (starter, main, dessert).  
- Bills generated per reservation, including food and service charges.  
- Waiters assigned to serve reservations.

### ER Diagram:
<img width="817" height="691" alt="image" src="https://github.com/user-attachments/assets/d4660005-47c1-4065-ad1b-18534f32dec0" />


### Entities and Attributes
<img width="445" height="212" alt="image" src="https://github.com/user-attachments/assets/5ed9596f-487d-495d-8aab-f5002d32c8a8" />


### Relationships and Constraints
<img width="416" height="163" alt="image" src="https://github.com/user-attachments/assets/cb4719d1-2ba0-4db4-a5dd-e700f4c07704" />


### Assumptions
- Each customer has a unique Customer_ID.
- Customers can make reservations or walk in.
- Each reservation is assigned a table and waiter.
- A reservation can have multiple food orders.
- Each order contains one or more dishes.
- Each dish belongs to one category.
- Each reservation generates one bill.
- The bill includes food and service charges.

---

## Instructions for Students

1. Complete **all three scenarios** (A, B, C).  
2. Identify entities, relationships, and attributes for each.  
3. Draw ER diagrams using **draw.io / diagrams.net** or hand-drawn & scanned.  
4. Fill in all tables and assumptions for each scenario.  
5. Export the completed Markdown (with diagrams) as **a single PDF**
