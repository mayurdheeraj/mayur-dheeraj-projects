# MongoDB Lab - Student Marks

## Task 2: Setup
- *Cluster*: cluster0 Atlas
- *Database*: student_marks_db 
- *Collection*: students

## Task 3: Insert
- *Documents*: 5 students inserted
- *Source File*: data.json

## Task 4: Queries + Results

### 1. Find CSE Department
*Query*: { "department": "CSE" }
*Count*: 2
*Result*: S001 Rahul Sharma, S004 Sneha Reddy

### 2. Find Total Marks > 250
*Query*: { "total": { "$gt": 250 } }
*Count*: 3
*Result*: S001 Rahul Sharma, S002 Priya Patel, S004 Sneha Reddy

### 3. Find Maths Marks > 80
*Query*: { "marks.maths": { "$gt": 80 } }
*Count*: 3
*Result*: S001 Rahul Sharma, S002 Priya Patel, S004 Sneha Reddy
