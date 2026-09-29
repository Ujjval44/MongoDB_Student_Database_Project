# MongoDB_Student_Database_Project
📚 MongoDB Student Database Project | Complete CRUD operations, query operators, student records management, and MongoDB Shell (mongosh) commands for academic/practical use.
# 📚 MongoDB Student Database Operations

A complete academic MongoDB project demonstrating student database management using **MongoDB Shell (mongosh)**. This project covers database creation, student record insertion, updating, deletion, querying, and verification operations.

---

## 📌 Project Overview

The **MongoDB Student Database Project** demonstrates practical **NoSQL database operations** using MongoDB.

The project uses:

* **Database:** `studentProjectDB`
* **Collection:** `studentRecords`
* **Initial Records:** 51
* **Roll Numbers:** 201–251

The project covers **Insert, Update, Delete, Query, and Verification operations**.

---

## 🛠️ Technologies Used

* **MongoDB**
* **MongoDB Shell (mongosh)**
* **NoSQL Database**
* **MongoDB Query Language**

---

## 📂 Project Structure

```text
MongoDB-Student-Database-Operations/
│
├── README.md
│
└── MongoDB_Student_Database_Project.pdf
```

---

## 🗄️ Database Details

| Property        | Value                   |
| --------------- | ----------------------- |
| Database Name   | `studentProjectDB`      |
| Collection Name | `studentRecords`        |
| Initial Records | 51                      |
| Roll Numbers    | 201–251                 |
| Database Type   | NoSQL                   |
| Tool            | MongoDB Shell (mongosh) |

---

## 📊 Student Record Structure

Each student record contains information such as:

```text
rollNo
name
age
department
marks
```

Some update operations also demonstrate the use of:

```text
status
```

### Example Student Record

```json
{
  "rollNo": 201,
  "name": "Aarav",
  "age": 21,
  "department": "CSE",
  "marks": 86
}
```

---

# 🔄 Operations Covered

## 1. Create / Select Database

The project uses the following MongoDB database:

```text
studentProjectDB
```

---

## 2. Insert One

Demonstrates inserting a single student record into the `studentRecords` collection.

Example student:

```text
Roll No.: 201
Name: Aarav
Age: 21
Department: CSE
Marks: 86
```

---

## 3. Insert Many

Demonstrates inserting multiple student records.

The project contains records from:

```text
Roll No. 202 – 251
```

Departments include:

* CSE
* IT
* ECE
* ME

---

## 4. Update One

Demonstrates updating a particular student's record.

Example:

```text
Roll No. 201
Marks: 86 → 90
```

---

## 5. Update Many

Demonstrates updating multiple documents based on a condition.

Example:

```text
CSE students → status: "Active"
```

---

## 6. Delete One

Demonstrates deleting a specific student record.

Example:

```text
Roll No. 251
```

---

## 7. Delete Many

Demonstrates deleting multiple records based on a condition.

Example:

```text
Marks < 40
```

---

# 🔎 Query Operations

The project demonstrates several MongoDB comparison operators.

### `$gt` — Greater Than

Find students whose marks are greater than 80.

```text
marks > 80
```

### `$lt` — Less Than

Find students whose marks are less than 80.

```text
marks < 80
```

### `$eq` — Equal To

Find students whose marks are exactly 85.

```text
marks = 85
```

### `$gte` — Greater Than or Equal To

Find students whose marks are greater than or equal to 80.

```text
marks >= 80
```

### `$ne` — Not Equal To

Find students whose marks are not equal to 85.

```text
marks ≠ 85
```

---

# 🧠 Logical Operators

## `$and`

Find students satisfying both conditions:

```text
Marks > 70
AND
Age < 23
```

---

## `$or`

Find students belonging to either:

```text
CSE
OR
ECE
```

---

## `$not`

Find students whose marks are **not greater than 80**.

---

# 📋 Verification Operations

The project also demonstrates basic database verification commands, including:

* Show current database
* Show collections
* Display all student records
* Display records in readable format
* Count total documents
* Count CSE students
* Count ECE students
* Count IT students
* Count ME students

---

# 🔍 Student Search Operations

The project demonstrates different ways to search student records.

### Find Student by Roll Number

Example:

```text
Roll No. 201
```

### Find CSE Students

Retrieves all students belonging to the CSE department.

### Find ECE Students

Retrieves all students belonging to the ECE department.

### Find IT Students

Retrieves all students belonging to the IT department.

### Find ME Students

Retrieves all students belonging to the ME department.

---

# 🎯 Learning Objectives

This project provides practical understanding of:

* NoSQL databases
* MongoDB databases
* Collections and documents
* CRUD operations
* MongoDB Shell
* MongoDB query operators
* Comparison operators
* Logical operators
* Updating documents
* Deleting documents
* Searching and filtering records
* Counting documents
* Database verification

---

# 🚀 How to Use

### Step 1 — Install MongoDB

Install MongoDB and MongoDB Shell (`mongosh`) on your computer.

### Step 2 — Open MongoDB Shell

Run:

```text
mongosh
```

### Step 3 — Select the Database

Use:

```text
studentProjectDB
```

### Step 4 — Access the Collection

The collection used in this project is:

```text
studentRecords
```

### Step 5 — Follow the Practical

Refer to the project PDF for the complete questions, MongoDB commands, and output/screenshot sections.

---

# 📄 Project Documentation

The repository includes:

### `MongoDB_Student_Database_Project.pdf`

The PDF contains the complete practical documentation, including:

* Project information
* Database and collection details
* Insert operations
* Update operations
* Delete operations
* Query operations
* Comparison operators
* Logical operators
* Verification commands
* Student search operations
* Output / screenshot sections

---

# 🎓 Academic Information

| Field       | Details                          |
| ----------- | -------------------------------- |
| **Project** | MongoDB Student Database Project |
| **Course**  | NoSQL and DBaaS                  |
| **Program** | BCA DS & AI                      |
| **Session** | 2026–2027                        |

---

# 👨‍💻 Author

**Ujjval Singh**

BCA DS & AI

---

# ⭐ Project Highlights

```text
✓ MongoDB NoSQL Database
✓ Student Records Management
✓ CRUD Operations
✓ Insert One & Insert Many
✓ Update One & Update Many
✓ Delete One & Delete Many
✓ Comparison Operators
✓ Logical Operators
✓ Department-wise Searching
✓ Document Counting
✓ Database Verification
✓ Academic Practical Project
```

---

## 📜 License

This project is created for **educational and academic purposes**.

You are welcome to study and use the concepts demonstrated in this project for learning and practical practice.

---

## ⭐ Support

If you found this project useful for learning MongoDB, consider giving the repository a ⭐ on GitHub.
