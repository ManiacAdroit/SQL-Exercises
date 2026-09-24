# SQL Functions and Query Operations

## 📋 Overview
This repository contains a collection of SQL exercises that introduce essential SQL functions and query operations used for data analysis and database management. The exercises focus on performing calculations, manipulating dates, combining data from multiple tables, handling missing values, and merging query results.

These concepts form the foundation of writing efficient SQL queries for reporting, business intelligence, and data analytics.

## 🎯 Learning Objectives
After completing these exercises, you should be able to:
* Retrieve data using standard query filters.
* Use aggregate functions to summarize data.
* Apply SQL operators to filter and compare data.
* Manipulate and format dates using date functions.
* Retrieve related data using different types of joins.
* Handle `NULL` values effectively.
* Combine the results of multiple queries using `UNION` and `UNION ALL`.

---

## 📂 Exercises Covered

### 🔹 Exercise 1 – SQL Fundamentals
#### Description
This foundational exercise introduces core data retrieval techniques, focusing on extracting target fields out of database tables, filtering rows, and sorting outputs.

#### Topics Covered
* **Basic Selection:** `SELECT *` (all columns) vs. explicit column mapping.
* **Deduplication:** Removing redundant values using `DISTINCT`.
* **Sorting Records:** Ordering query output in ascending or descending blocks using `ORDER BY`.
* **Row Limits:** Constraining results using the `LIMIT` clause.
* **Basic Filtering:** Building row filters using the `WHERE` clause combined with conditional logic.

#### Learning Outcomes
* Query individual database columns efficiently.
* Clean result sets by pulling unique attribute combinations.
* Sort records to isolate top performing metrics or chronological order.
* Isolate target data scopes using foundational `WHERE` parameters.

---

### 🔹 Exercise 2 – SQL Aggregates and Operators
#### Description
This exercise introduces aggregate functions used to summarize data and SQL operators used to filter and compare records.

#### Topics Covered
* **Aggregate Functions:** `COUNT()`, `SUM()`, `AVG()`, `MIN()`, `MAX()`
* **SQL Operators:**
  * Arithmetic Operators (`+`, `-`, `*`, `/`)
  * Comparison Operators (`=`, `>`, `<`, `>=`, `<=`, `<>`)
  * Logical Operators (`AND`, `OR`, `NOT`)
  * Range & Pattern Matching (`BETWEEN`, `IN`, `LIKE`)

#### Learning Outcomes
* Calculate totals and averages.
* Count records.
* Identify minimum and maximum values.
* Filter records using complex conditions.
* Combine multiple conditions seamlessly in SQL queries.

---

### 🔹 Exercise 3 – Date Functions
#### Description
This exercise focuses on working with date and time values in SQL.

#### Topics Covered
* Current date and time systems.
* Extracting structural date components.
* Date arithmetic and interval calculations.
* Formatting dates for clean reporting.
* Calculating explicit differences between temporal markers.

#### Common Functions
`CURRENT_DATE` | `CURRENT_TIMESTAMP` | `NOW()` | `YEAR()` | `MONTH()` | `DAY()` | `DATEDIFF()` | `DATEADD()`

#### Learning Outcomes
* Retrieve the active system date.
* Extract year, month, and day values from standard timestamps.
* Calculate the elapsed operational difference between dates.
* Perform calculations required for rolling timeframes and cohort analysis.

---

### 🔹 Exercise 4 – Joins
#### Description
This exercise introduces SQL joins, which combine related data from multiple tables based on matching key columns.

#### Types of Joins Covered
* **`INNER JOIN`** – Returns matching records present in both tables.
* **`LEFT JOIN`** – Returns all records from the left table and matching fields from the right table.
* **`RIGHT JOIN`** – Returns all records from the right table and matching fields from the left table.
* **`FULL OUTER JOIN`** – Returns all matching and non-matching records across both source tables.

#### Learning Outcomes
* Combine normalization boundaries across database architectures.
* Map and trace relationships between core schemas.
* Retrieve complete datasets without losing critical null matches.

---

### 🔹 Exercise 5 – NULL Functions
#### Description
This exercise focuses on managing missing, placeholder, or unknown data entries stored as `NULL`.

#### Topics Covered
* Understanding data exceptions and `NULL` structures.
* Replacing empty attributes dynamically.
* Logic evaluation for missing data fields.

#### Common Functions
`COALESCE()` | `IFNULL()` (MySQL) | `ISNULL()` (SQL Server) | `NULLIF()`

#### Learning Outcomes
* Detect missing attributes within columns safely.
* Substitute default semantic replacements in place of empty fields.
* Prevent arithmetic data calculation drops due to `NULL` ingestion.
* Improve query stability and structural accuracy.

---

### 🔹 Exercise 6 – UNION / UNION ALL
#### Description
This exercise demonstrates how to append the execution sets of two or more independent `SELECT` statements together vertically.

#### Operations Mastered
* **`UNION`** – Combines query streams while filtering out duplicate records. Requires matching schema counts and structurally compatible data domains.
* **`UNION ALL`** – Combines query sets while keeping all records intact. Executes faster as it bypasses deduplication indexing tasks.

#### Learning Outcomes
* Merge segmented data elements across decoupled histories.
* Make technical decisions between executing a `UNION` vs a `UNION ALL` based on scaling priorities.

---

## 🛠️ Skills Developed
By completing these exercises, you will develop the ability to:
* Navigate structural relational database tables using standardized queries.
* Summarize high-volume tables cleanly using aggregation tools.
* Narrow evaluation logic via conditional processing operators.
* Parse complex historical variables with timestamp formulas.
* Reconnect distributed tables safely across cross-functional operations.
* Standardize data inputs and patch database gaps.
* Package clean reporting frameworks.

---

## 🏁 Prerequisites
Before attempting these exercises, ensure you possess basic working knowledge of:
* Core database relational patterns.
* Primary data manipulation queries (`SELECT`, `FROM`, `WHERE`, `ORDER BY`).

## 📈 Applications
The SQL concepts taught within this curriculum map directly to professional operations in:
* **Data Analytics & Reporting**
* **Business Intelligence (BI) Pipelines**
* **Database Administration & Design**
* **Financial Audits & Forecasting**
* **CRM & Inventory Asset Management**

---

## 💡 Conclusion
These exercises provide direct experience working with fundamental SQL functions and query variations that drive modern relational databases. Mastering aggregates, operators, date calculations, relational joins, null strategies, and set logic establishes the groundwork required to extract value from data and prepare for advanced analytical engineering tracks.
