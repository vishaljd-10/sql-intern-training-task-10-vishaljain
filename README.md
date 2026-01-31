

# Task: Working with SQL Views Using Projects Data

## Objective

Understand how SQL Views can be created and used with **projects** and **departments** tables to make queries easier and support reporting needs.

## Tools Used

* MySQL Workbench
* Other options: PostgreSQL, SQLite, BigQuery Sandbox

---

## Tables Involved

1. departments
2. projects

---

## Concepts Learned

* Creating SQL Views
* Using JOINs
* Applying filters and sorting
* Building reporting views
* Understanding insert limitations
* Safely dropping and recreating views

---

## Step-by-Step Execution

### 1. Table Creation

* Created the departments table
* Created the projects table with a foreign key reference

### 2. Data Insertion

Inserted sample project data mapped to different departments.

### 3. Writing a Complex Query

Used JOIN operations to fetch:

* Project name
* Budget
* Department name
* Department location

### 4. View Creation

Converted the JOIN query into a SQL VIEW for reuse.

### 5. Querying the View

Accessed the view just like a normal table.

### 6. Applying Filters and Sorting

Used WHERE and ORDER BY clauses on the view.

### 7. Insert Restrictions

Tried inserting data through the view and observed limitations.

### 8. Reporting View

Designed an aggregated view to display:

* Number of projects per department
* Average project budget

---

## Benefits of Using Views

✔ Makes complex queries easier
✔ Enhances data security
✔ Useful for reporting and dashboards
✔ Encourages reusable query logic

---

## Limitations of Views

✖ Restricted insert and update operations
✖ Possible performance impact
✖ Dependent on underlying tables

---

## Final Result

The intern is now able to:

* Create and manage SQL Views
* Use views for analytical reporting
* Identify limitations of views
* Design reusable data abstraction layers

---
