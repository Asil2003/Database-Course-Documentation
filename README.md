# 📘 Database Course Documentation

This repository contains a comprehensive report covering key concepts in database systems .

---

## 1️⃣ Flat File Systems vs. Relational Databases

| Feature         | Flat File Systems                 | Relational Databases                   |
|----------------|-----------------------------------|----------------------------------------|
| Structure       | Single table or document (e.g., CSV) | Organized into multiple related tables |
| Data Redundancy | High – same data repeated         | Low – normalization reduces repetition |
| Relationships   | Not supported                     | Supported via primary/foreign keys     |
| Example Usage   | Excel sheets, simple data storage | Web apps, ERPs, banking systems        |
| Drawbacks       | Poor scalability, redundancy      | Requires schema design, setup overhead |

📌 **Summary**: Flat file systems are suitable for simple use cases, while relational databases provide structure, scalability, and consistency for complex data operations.

---

## 2️⃣ DBMS Advantages – Mind Map

🧠 Below is a mind map showing the key advantages of a DBMS.

![DBMS Mind Map](images/dbms_mind_map.png)


*Image created using [Mindmup]((https://app.mindmup.com/))*

---

## 3️⃣ Roles in a Database System

Understanding who does what in a database project is crucial. Below are key roles and their responsibilities:

| Role                     | Description |
|--------------------------|-------------|
| **System Analyst**       | Gathers user requirements and analyzes how the system should behave. Acts as a bridge between users and developers. |
| **Database Designer**    | Designs the database schema including tables, fields, relationships, and constraints based on system requirements. |
| **Database Developer**   | Implements the design using SQL and DBMS tools. Writes queries, procedures, and ensures data is stored efficiently. |
| **Database Administrator (DBA)** | Manages the database's day-to-day operations: security, backups, performance tuning, user roles, and disaster recovery. |
| **Application Developer**| Integrates the database with software applications (web/mobile). Uses SQL or ORM tools to fetch and update data. |
| **BI Developer**         | Uses the data in the database to build reports, dashboards, and analytical models for business decision-making. |

📌 **Note:** In small teams, some of these roles may be combined, while in larger enterprises, they are often specialized.



---

## 4️⃣ Types of Databases

Understanding different types of databases helps in choosing the right one based on the application’s needs.

---

### 🔄 Relational vs. Non-Relational

| Type             | Description                                                                 | Examples              |
|------------------|-----------------------------------------------------------------------------|-----------------------|
| **Relational**   | Uses structured tables with rows and columns. Supports SQL queries and relationships through keys. | MySQL, PostgreSQL, Oracle |
| **Non-Relational** | Uses flexible formats like documents, key-value pairs, graphs, or columns. Suitable for big data and fast-changing data. | MongoDB, Cassandra, Firebase |

---

### 🗺️ Centralized vs. Distributed vs. Cloud Databases

| Type             | Description                                                                 | Example Use Case                |
|------------------|-----------------------------------------------------------------------------|----------------------------------|
| **Centralized**   | All data is stored and managed in a single location or server.             | Small business inventory system |
| **Distributed**   | Data is spread across multiple servers or locations but appears as one system. | Global banking or e-commerce   |
| **Cloud**         | Data is hosted by third-party providers with on-demand scalability.         | Web and mobile apps (e.g., Amazon RDS) |

📌 **Tip:** Distributed and cloud databases are often combined in modern applications to ensure high availability and performance.


---

## 5️⃣ Cloud Storage and Databases

Modern applications increasingly rely on cloud-based storage and database systems. Here's what you need to know:

---

### ☁️ What is Cloud Storage?

Cloud storage is a model where data is stored on remote servers accessed through the internet. These storage services are maintained by cloud providers like AWS, Azure, or Google Cloud.

In database systems, cloud storage is used for:
- Hosting databases (e.g., Amazon RDS, Azure SQL)
- Storing backups
- Providing access to data from anywhere

---

### ✅ Advantages of Cloud-Based Databases

- **Scalability**: Resources can grow with user demand.
- **High Availability**: Data is accessible 24/7 with failover support.
- **Cost Efficiency**: Pay-as-you-go model avoids infrastructure costs.
- **Managed Services**: Providers handle maintenance, security, and updates.
- **Global Access**: Data and apps can be accessed from anywhere.

---

### ⚠️ Disadvantages and Challenges

- **Internet Dependency**: No access without an internet connection.
- **Ongoing Cost**: Monthly/usage-based billing can add up.
- **Data Privacy**: Risk of data exposure if not properly secured.
- **Limited Control**: You don’t manage the physical infrastructure.

---

### 💡 Examples of Cloud-Based Database Services

| Service               | Provider         |
|-----------------------|------------------|
| Amazon RDS            | AWS              |
| Azure SQL Database    | Microsoft Azure  |
| Google Cloud Spanner  | Google Cloud     |
| Firebase Firestore    | Google Cloud     |
| MongoDB Atlas         | MongoDB (Cloud)  |

📌 **Summary**: Cloud databases offer flexibility and convenience but must be managed wisely to ensure security and cost control.


---

## 📋 Conclusion

This report summarizes the essential concepts of database systems including structure comparison, system roles, database types, and the future of cloud-based databases.

---

## 📁 Files Included

- `README.md` – main report
- `/images/` – contains DBMS mind map and other visuals
