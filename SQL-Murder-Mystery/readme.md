# 🕵️ SQL Murder Mystery – Complete Investigation Using SQL
## 📌 Project Overview:
This repository contains a complete, step-by-step solution to the SQL Murder Mystery challenge. The goal of this project is to solve a fictional murder case using only SQL, exploring relational data, analyzing witness interviews, and narrowing down suspects through logical filtering.<br>

### This project demonstrates real-world SQL problem-solving skills, including:
- Data exploration and querying
- Debugging empty or unexpected result sets
- Combining information across multiple related tables

🧠 Problem Statement
- A murder took place on January 15, 2018, in SQL City. Using the available database, the objectives are:
  1. Identify the murderer
  2. Identify the mastermind who hired the murderer<br>
All conclusions are derived purely using SQL queries.

## 🔗 Dataset & Environment: 
### This project uses the official SQL Murder Mystery database, available at:
- https://mystery.knightlab.com/
### The platform provides:
- A preloaded relational database
- An in-browser SQL editor
- All required tables available by default
- No database setup or data import needed

## 🗂️ Database Tables Used:
- The investigation involves multiple related tables:
  - crime_scene_report
  - person
  - interview
  - drivers_license
  - get_fit_now_member
  - get_fit_now_check_in
  - facebook_event_checkin
  - income
- These tables are linked using primary and foreign keys, requiring extensive use of JOINs to combine data effectively.

## 🔍 Investigation Approach:<br>
Instead of attempting a single complex query, the investigation followed a structured, step-by-step approach:

1️⃣ Crime Analysis:
-  Queried the crime_scene_report table to identify crime details
-  Extracted location, date, and witnesses

2️⃣ Witness Identification & Interviews:
-  Identified two witnesses using address clues
-  Retrieved interview transcripts to extract critical information:
-  Gym membership and type
-  Vehicle plate number patterns
-  Physical descriptions

3️⃣ Suspect Filtering:
-  Narrowed suspects using Get Fit Now Gym membership
-  Applied Gold membership and membership ID pattern (48Z)
-  Cross-checked suspects using vehicle plate information
-  ✅ Result: Murderer identified as Jeremy Bowers

## 🧩 Mastermind Identification:
Used the murderer’s interview to find the person who hired him:
Height: 65–67 inches
Drives a Tesla Model S
Attended the SQL Symphony Concert
High annual income
Combined drivers_license, facebook_event_checkin, and income data to identify the mastermind
✅ Result: Mastermind identified as Miranda Priestly

## 🛠️ SQL Concepts Demonstrated:
-  This project demonstrates practical usage of:
-  INNER JOINs
-  Subqueries
-  Filtering using WHERE
-  Pattern matching using LIKE
-  Sorting and limiting results using ORDER BY and LIMIT
-  Progressive query debugging
-  Data validation using DISTINCT

## ▶ How to Run the Project:
-  Visit SQL Murder Mystery
-  Open the built-in SQL editor
-  Copy queries from sql_murder_mystery_solution.sql
-  Execute queries step by step following the comments in the file

## 🏁 Final Answer :
-  🔍 Murderer: Jeremy Bowers
-  🧠 Mastermind: Miranda Priestly

## 👨‍💻 Author<br>
Vaibhav Dhakulkar<br>
Data Analyst | SQL | PL/SQL | Python | Excel

## ⭐ Support:
If you find this repository useful, please consider supporting me by:
- ⭐ Starring this repository
- 👍 Liking and sharing my content
- 🔁 Sharing with your friends and network
- 💬 Giving your valuable feedback
- 
## 🔗 Connect with Me : 
📌 Email: vaibhavdhakulkar1998@gmail.com
📌 Follow me on LinkedIn: https://www.linkedin.com/in/vaibhavdhakulkar25<br>
📌 Subscribe to my YouTube channel: https://www.youtube.com/@VaibhavRajAsha<br>
