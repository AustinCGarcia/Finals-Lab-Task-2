# [Finals Lab Task 2](https://github.com/user-attachments/files/19717664/GARCIA.-.LAB.TASK.2.-.FINALS.docx)

– This portfolio showcases my knowledge of creating a MySQL database through a simplified student assignment submission system. It includes the step-by-step development of tables for students, assignments, and their submissions. The task highlights the use of data types, relationships, and constraints such as primary keys, foreign keys, and composite keys to construct a complete and functional relational schema.

# Step By Step Process
### 1. Create the student table:
- Define username as a VARCHAR(50).
- Set username as the Primary Key.

### 2. Create the assignment table:
- Define shortname as a VARCHAR(50) and set it as the Primary Key.
- Define due_date as a DATE NOT NULL.
- Define url as a VARCHAR(255), which can be null.

### 3. Create the submission table:
- Define username and shortname both as VARCHAR(50).
- Define version as an INT.
- Define submit_date as a DATE NOT NULL.
- Define data as TEXT.
- Set a composite primary key of (username, shortname, version).
- Add foreign keys referencing the student and assignment tables.

# Screenshots
## Query Statements
1. Student Table
<img width="227" alt="Image" src="https://github.com/user-attachments/assets/8bdbad77-9a8f-4992-917f-559bd9d53bf6" />

2. Assignment Table
<img width="229" alt="Image" src="https://github.com/user-attachments/assets/70ed6bf5-453c-458d-b311-d7f9a2bb9858" />

3. Submission Table
<img width="392" alt="Image" src="https://github.com/user-attachments/assets/722d023b-5fd7-435b-88c4-d381c9560514" />

## Table Structure
1. Student Table
<img width="260" alt="Image" src="https://github.com/user-attachments/assets/830bde1a-3943-49e0-9cf5-aab5dba45839" />

2. Assignment Table
<img width="265" alt="Image" src="https://github.com/user-attachments/assets/44c280bb-3380-4cba-9e9b-f80fe4b66ff2" />

3. Submission Table
<img width="267" alt="Image" src="https://github.com/user-attachments/assets/bddfdd25-17a7-4b30-9894-890f7b52ba70" />

## EER Diagram
<img width="545" alt="Image" src="https://github.com/user-attachments/assets/519ab790-1653-4e00-b11e-982bf68a22c0" />
<img width="503" alt="Image" src="https://github.com/user-attachments/assets/eb123687-e0b1-45c3-8e06-29ac17905c79" />
