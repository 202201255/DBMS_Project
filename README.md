
#  IPL Database Management System Project

This project is a **Database Management System (DBMS)** for managing **IPL (Indian Premier League)** related data. It includes all core DBMS concepts such as **ER Diagram**, **Relational Schema**, **Normalization Proofs**, **SQL Scripts for Insertion**, and **SQL Queries** for various operations and analysis.

---

##  Table of Contents

1. [Project Overview](#project-overview)
2. [Entity-Relationship (ER) Diagram](#er-diagram)
3. [Relational Schema](#relational-schema)
4. [Normalization](#normalization)
5. [Insert Scripts](#insert-scripts)
6. [SQL Queries](#sql-queries)
7. [Technologies Used](#technologies-used)
8. [How to Run](#how-to-run)
9. [Future Scope](#future-scope)

---

##  Project Overview

This project demonstrates how to build a structured IPL database from scratch using key DBMS concepts. The data includes:

* Teams and Players
* Matches and their details
* Statistics and Performance
* Venues and Officials
* Sponsors and Audience details

The database was designed with the aim to:

* Apply real-world DBMS principles
* Practice ER modeling and schema creation
* Write normalized and efficient SQL queries

---

##  ER Diagram

* The **ER Diagram** defines the high-level structure of the IPL database.
* It shows relationships between entities like `Team`, `Player`, `Match`, `Venue`, etc.
* Relationships include:

  * Players belong to a team
  * Matches are played between teams at a venue
  * Each match has a result and umpire details

📁Refer to: [`ER_Diagram.png`](./ER_Diagram.png)

---

##  Relational Schema

* Converted from the ER diagram.
* Each entity and relationship is represented as a table with proper primary and foreign keys.
* Ensures data is properly linked and consistent.

📁 Refer to: [`Relational_Schema.txt`](./Relational_Schema.txt)

---

##  Normalization

Normalization helps to reduce redundancy and avoid anomalies.

This project goes through:

* **1NF (First Normal Form)** – Atomic values in all attributes.
* **2NF (Second Normal Form)** – No partial dependency.
* **3NF (Third Normal Form)** – No transitive dependency.
* **BCNF (Boyce-Codd Normal Form)** – Every determinant is a candidate key.

📁 Proof of each step is provided in [`Normalization.txt`](./Normalization.txt)

---

##  Insert Scripts

* Pre-written **SQL INSERT statements** to populate tables with sample IPL data.
* Helps simulate a working IPL database.

📁 File: [`Insert_Script.txt`](./Insert_Script.txt)

---

##  SQL Queries

Set of meaningful SQL queries like:

* Retrieve top-scoring players
* List matches played in a specific city
* Get win stats of a team
* Find most valuable players

📁 File: [`Queries.txt`](./Queries.txt)

---

##  Technologies Used

* **MySQL / PostgreSQL** (can run on either)
* SQL syntax for schema creation and data manipulation
* DBMS principles: ER modeling, normalization, constraints

---

##  How to Run

1. Clone the repo:

   ```
   git clone https://github.com/rathodjay19/DBMS_Project
   cd DBMS_Project
   ```
2. Open your SQL database environment (MySQL Workbench / pgAdmin / DBeaver).
3. Create tables as per the relational schema.
4. Run the `Insert_Script.txt` to populate data.
5. Execute queries from `Queries.txt` to test functionalities.

---

## 🚀 Future Scope

* Add triggers and stored procedures
* Implement constraints like `ON DELETE CASCADE`
* Build a web interface using PHP/Python and connect the database

---

