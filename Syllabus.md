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

## **Generative AI Usage Guidelines**

## 1. Purpose of These Guidelines
Generative AI tools (e.g., ChatGPT, GitHub Copilot, Claude) can support your learning by explaining concepts, suggesting code examples, and offering design guidance. However, the **primary goal of this course** is for you to personally develop the skills, not rely solely on ready-made answers. These guidelines ensure deep learning, academic honesty, and ethical use.



## 2. Allowed Uses
You are encouraged to use generative AI tools for the following purposes:

- **Explaining Concepts**  
  Asking about differences, applications, or underlying theory (e.g., the difference between INNER JOIN and LEFT JOIN in SQL).

- **Debugging Guidance**  
  Asking what a specific error means and exploring strategies to fix it.

- **Best Practices**  
  Example: “How should I manage database connections securely in Python?”

- **Exploring Libraries and Tools**  
  Example: “Which libraries are available for connecting Python to PostgreSQL?”

- **Improving Code Readability or Design**  
  Requesting feedback to simplify queries or optimize algorithms.

- **Comparing Approaches**  
  Example: “What are the advantages of SQL vs. NoSQL, or Pandas vs. PySpark?”

- **Learning Through Simple Examples**  
  Understanding patterns and structures without requesting final answers to assignments.



## 3. Prohibited Uses
Please **do not** use generative AI tools for the following:

- **Directly Solving Course Assignments or Projects**  
  Requesting final code or answers for graded work.

- **Bypassing the Learning Process**  
  Copying AI-generated solutions without understanding them.

- **Sharing Proprietary Course Content**  
  Posting full assignment or project descriptions into AI tools.

- **Using AI as the Only Source**  
  Ignoring course notes, lectures, and official documentation.



## 4. Transparency and Academic Integrity
- If you used generative AI in your work, **disclose it clearly** and explain how you used it (e.g., “I used ChatGPT to help explain a SQL error”).  
- Any misuse (e.g., submitting AI-generated answers as your own) violates academic honesty policies and may result in disciplinary action.



## 5. Examples

### 5.1 Acceptable Questions
- “How can I remove duplicate records in SQL?”
- “What is the difference between INNER JOIN and LEFT JOIN in SQL?”
- “What visualization tools are available in Python that are similar to Power BI?”
- “Is there a more efficient way to normalize this database schema?”

### 5.2 Unacceptable Questions
- “Write the solution for Question 3 of Week 5’s assignment.”
- “Generate the complete code for the final project.”
- “Optimize this exact query from my homework and give me the final answer.”
- “Provide me with a ready-to-submit file for this task.”


## 6. Best Practices for Using Generative AI
- Treat AI responses as **guidance**, not final solutions.  
- Use AI to **enhance your understanding**, not replace your own problem-solving.  
- Ensure **progressive learning**: try solving on your own first, then use AI for clarification.



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
