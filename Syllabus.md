---
layout: page
title: Syllabus
permalink: /Syllabus/
---
# **Course Overview**

This course bridges **data analysis** and **database management systems (DBMS)**, focusing on both the **design** of relational databases and their use in **modern analytical workflows**. Students will learn how to structure data, query it efficiently, and perform local analytics with modern tools.

The course is structured into **two main parts**:

1. **Database Design and SQL with PostgreSQL**
   - Fundamentals of **Entity-Relationship (ER) modeling** and converting ER diagrams into **relational schemas**.  
   - Writing **basic to advanced SQL queries** for data retrieval, manipulation, and aggregation.  
   - Implementing database designs using **PostgreSQL** for reliable and scalable data management.  

2. **Data Analysis and Local Analytics with DuckDB**
   - Performing **analytical workflows** using **DuckDB** for fast, local data exploration.  
   - Importing, cleaning, and analyzing **real datasets (CSV, Parquet)** directly from storage.  
   - Integrating with **Python (Pandas)** and visualization tools for in-depth data insights.  
   - Understanding the difference between **analytical (OLAP)** and **transactional (OLTP)** databases in practical applications.  

# **Course Objectives**

By the end of this course, students will:  
- Understand the **fundamentals of database theory** and their role in data-driven workflows.  
- Design **ER models** and implement them as relational databases using PostgreSQL.  
- Formulate **SQL queries** for preparing, aggregating, and transforming data.  
- Utilize **DuckDB** for local analytics and fast exploration of datasets.  
- Connect databases to **Python (Pandas)** for advanced data analysis and computation.  
- Use **visualization tools (Power BI, Streamlit)** to create dashboards and present insights interactively.  
- Deliver a **final project** that combines database design, SQL, and analytical reporting in a cohesive workflow.  

# **Hands-on Environment**

- **PostgreSQL**: For relational database design and SQL practice.  
- **DuckDB**: For local analytics and fast data exploration.  
- **Python (Pandas)**: For data cleaning and analysis.  
- **Power BI / Streamlit**: For visualization and interactive reporting.


# **Weekly Course Outline**
> [!NOTE]
> **Important:**  
> The weekly topics may be subject to minor adjustments. Some topics might be added, removed, or shifted slightly during the course based on class progress and feedback.



## **Introduction to Databases and Data Concepts**
- Course structure, grading, and project overview.  
- Introduction to **data and data analysis**: structured vs unstructured data.  
- Overview of **big data** and its characteristics. 
- Types of data analytics: **descriptive, diagnostic, predictive, prescriptive**.  
- Definition and purpose of **database management systems (DBMS)**.  
- Basic database terminology (tables, rows, columns, keys).  

---

## **Overview of Database Models and ER Design**
- Types of database models: hierarchical, network, relational, NoSQL (overview).  
- Introduction to **Entity-Relationship (ER) modeling)**.  
- Entities, attributes, relationships, and cardinality.  
- Conceptual modeling for real-world datasets.  
- Weak entities and composite attributes. 
- Multi-valued attributes and derived attributes.  
---

## **Relational Model and Mapping ER to Relational Schema**
- Introduction to the relational model (tables, primary keys, foreign keys).  
- Mapping ER diagrams to relational tables.  
- Constraints and integrity rules.  
- Example: converting an ER diagram of a sample dataset into a relational schema.  

---

## **Introduction to PostgreSQL and Basic SQL**
- Setting up PostgreSQL and connecting via GUI/CLI.  
- Creating databases and tables.  
- Inserting, updating, and deleting records.  
- Simple queries: `SELECT`, `WHERE`, `ORDER BY`, `LIMIT`.  

---

## **Intermediate SQL Queries**
- Aggregate functions: `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`.  
- Grouping data with `GROUP BY` and filtering with `HAVING`.  
- Sorting and combining data with `JOIN` (inner, outer).  
- Practical exercises on real datasets.  

---

## **Advanced SQL Queries**
- Nested queries and subqueries.  
- Set operations: `UNION`, `INTERSECT`, `EXCEPT`.  
- Window functions (ranking, moving averages).  
- Query performance basics (indexes and execution plans – overview only).  

---

## **Introduction to Analytical Databases and DuckDB**
- Concept of **analytical databases** and how they differ from transactional ones (OLAP vs OLTP).  
- Introduction to **DuckDB** and why it’s useful for local analytics.  
- Setting up DuckDB and basic commands.  
- Importing CSV and Parquet files directly into DuckDB.  

---

## **Data Exploration with DuckDB**
- Querying datasets directly from storage (no ETL).  
- Combining DuckDB with **Pandas** for hybrid workflows.  
- Exploratory Data Analysis (EDA): summary statistics, filtering, grouping.  
- Hands-on: analyzing a sample dataset (e.g., population or survey data).  

---

## **Data Cleaning and Transformation**
- Handling missing data and outliers.  
- Converting data types and formatting.  
- Creating computed columns and derived tables.  
- Practical: preparing a dataset for analysis.  

---

## **Integrating Databases with Python**
- Connecting PostgreSQL and DuckDB with Python.  
- Executing queries and retrieving results programmatically.  
- Using **Pandas** for additional analysis and visualization.  
- Simple statistical operations within Python workflows.  

---

## **Data Visualization and Reporting**
- Basics of visualization tools: **Power BI** and **Streamlit**.  
- Connecting visualization tools to DuckDB/Postgres.  
- Building dashboards for interactive data reporting.  

---

## **Modern Trends in Databases (Overview)**
- NoSQL databases and their use cases (document, key-value, graph).  
- Vector databases and their role in semantic search and AI workflows.  
- Overview of query optimization and indexing (analytical perspective).  
- Future trends in analytical data management.  


## **Homework Assignments**

Throughout the course, students will complete several homework assignments aimed at reinforcing the concepts covered in lectures and reading materials (See the [homework page](https://statdb.ir/assignments/), which will be updated during the course). The due dates for these assignments will be posted on this website.

Please follow the instructions to turn in your homework:
- Homeworks must be submitted electronically as PDF files.
- Files should be named according to the following scheme:
   - HW<2-digits homework number>\_\<LastName>\_\<FirstName>.pdf.
   - For instance, my first homework would be called HW01_Vazan_Milad.pdf.
   - 📧 Email your homework to **hw@statdb.ir**
  
⚠️ **Important:** Emails with this exact subject format will receive an automatic confirmation reply upon submission. If you do not receive this confirmation within **five minutes**, it means your email was not received.  

> The **deadline** for each assignment will be **announced separately**. An **automatic reminder** will be sent **one day before the deadline** to the email address you provided to the instructor during the **first session**.

> If the **deadline is extended**, students who have **not submitted** their assignment will receive another **automatic email** **one day before the new deadline**.


## **Exams**

The course will include **two exams**. Both exams will assess the required readings and topics covered in class. The first exam will be an "in-class" [midterm](https://statdb.ir/exams), while the second will be a [final exam](https://statdb.ir/exams) scheduled during the University's final examination period at the end of the semester.

**If you need to miss the midterm test due to illness or a family affliction, please contact me by email. A make-up exam for the midterm might be organized.**
{: 	.text-green-200 }

## **Attendance and Participation**

**Attendance is required**, and exceeding four absences may result in a penalty of up to 2 points off your total grade. Active participation in both in-class activities and the online message board is highly encouraged.

# **Grading**
- Class attendance and participation: **2** points 
- Homeworks: **5** points
- Final project: **5** points 
- Midterm exam (-----): **3** points
- Final exam (-----): **5** points 


## **Seeking Assistance**

Here are the available help resources, organized by the urgency of your issue:

### **Messaging**
Our course will utilize a Telegram group (link to be provided in class) as the primary communication platform for announcements and discussions. This is an ideal space for asking questions that can be answered by anyone. It's best to use this resource for non-urgent inquiries.

### **Talk with the Instructor**
For any issues at all, please reach out to the instructor:

- Speak with me before class  
- Raise your hand or speak up during class


## **Collaboration Policy**

You are encouraged to discuss the content of this course with anyone you like; however, it is essential to **maintain academic integrity** in your work. All homework assignments, projects, and exams must be completed independently, meaning you are not permitted to copy any part of another student’s solution, collaborate with others on your assignments, or use solutions from unauthorized sources, including the Internet. **Therefore, the solution you submit for each assignment must be solely your own, reflecting your understanding and effort.**


## **Required Tools and Accounts**

To successfully participate in this course, students are expected to prepare the following tools and accounts prior to the practical sessions:

- **Python**: [Install](https://www.python.org/downloads/) the latest stable version of Python for running scripts and interacting with databases.  
- **GitHub Account**: Create a [GitHub](https://github.com/) account.
- **Streamlit Account and GitHub Integration**: Link your GitHub account to [Streamlit](https://share.streamlit.io/) to deploy database-driven web applications.
- **[Visual Studio Code](https://code.visualstudio.com/download)**
- **[PostgreSQL](https://www.postgresql.org/download/)**
- **DuckDB**: Install DuckDB for lightweight, embedded database tasks and analytical queries.
- **[Power BI](https://powerbi.microsoft.com/)**: Used for data visualization and creating interactive dashboards to analyze database results. 
- **Marimo**: This will be used as the primary environment for interactive notebooks and coding sessions.
  > pip install "marimo[recommended]"
- **Pandas**:
  > pip install pandas
- **PySpark**:
  > pip install pyspark

 

### **Hardware Requirement**

For the SQL and practical sessions, students will need **a laptop or a smartphone** to follow along and complete in-class exercises.

## **Related Courses**
### Other Databases courses 
<!--- ### What is this course like in other places?--->
- [New York University - Database Design & Implementation](https://knowledge.kitchen/content/courses/database-design/schedule/)
- [UC Berkeley - Introduction to Database Systems](https://cs186berkeley.net/)
- [CARNEGIE MELLON UNIVERSITY - Database Systems](https://15445.courses.cs.cmu.edu/spring2024/schedule.html)
- [University of Washington - Introduction to Database Systems](https://courses.cs.washington.edu/courses/cse414/)
- [The University of Chicago - Introduction to Database Systems](https://classes.cs.uchicago.edu/archive/2023/spring/23500-1/)
- [University of Waterloo - CS 348: Introduction to Database Systems](https://cs.uwaterloo.ca/~smaiyya/cs348/)
- [NTHU - CS 471000 Introduction to Database Systems](https://nthu-datalab.github.io/db/)
- [The Ohio State University - Introduction to Database Systems](https://syllabi.engineering.osu.edu/syllabi/cse_3241)

## **A note on self care.** 
Please take care of yourself. Do your best to maintain a healthy lifestyle this semester by eating well, exercising, getting enough sleep and taking some time to relax. This will help you achieve your goals and cope with stress. 
