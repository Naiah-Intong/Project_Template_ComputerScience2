# 📌 Project Proposal (Draft)

## 📝 Project Title  
Attendance Checker

## 🔍 Problem Statement  
Regular attendance written on pen and paper can be altered by the person writing it.
It may give them a free pass from late admissions, absents, and make it seem they were there earlier.
This problem is prominent today because of modern elements, and late entries should be sanctioned accordingly.
We picked the attendance dataset because it tracks the attendance. 

## 🎯 Project Objectives  
Objective 1: To help future users to have a guide in coding. 
Objective 2: To practice coding features and master them. 

## ⚙️ Planned Features  
Your program must have **at least 5 features (minimum)**.  
We have provided **2 starter ideas** for each dataset — you must design **at least 3 additional features**.  

- Feature 1: *(Starter idea)*  
- Feature 2: *(Starter idea)*  
- Feature 3: *(Your own idea)*  
- Feature 4: *(Your own idea)*  
- Feature 5: *(Your own idea)*  

*(You may add more features if you like.)*  

## ⌨️ Planned Inputs and Outputs  

- **Inputs**  
  student ID, student name, dates

- **Outputs**  
  dates tardy, absent, present, or cutting classes

## 🧠 Logic Plan  
Describe your program’s logic:  

### Pseudocode  
---START

FOR EACH student:
    count how many days they were Present, Tardy, Absent
    score = Present + (Tardy / 2)
    rate = score / total days * 100
    show rate

FOR EACH student and each day:
    IF status is not Present, Tardy, or Absent:
        list it as an error

ASK for a date:
    FOR EACH student and each day:
        IF day matches the date:
            show name, ID, and status

END

## 📂 GitHub Repository Link  
Paste your GitHub repository link here:  
`https://github.com/username/project-proposal`  

---
