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

- Feature 1: Structures storage, records are a list of students, each with a student_id, name, and a "dates" list of date_status entries, so the program can loop over.
- Feature 2: Inconsistent Statuses, statuses include "Absent - Excused", "Absent - Unexcused", and "Cut Class" beyond Present/Tardy/Absent, so the code needs a scoring rule for what counts as present and a check that flags invalid values.
- Feature 3: Weighted Attendance Score,  turn text statuses into numeric credit, so a single late arrival isn't treated the same as cutting class.
- Feature 4: Status Allow-List Check, catch invalid data early instead of bad typos or any unrelated inputs. 
- Feature 5: Daily Roll Call Lookup, track student-grouped records into a single-day view for a quick attendance check for the entire class. 

*(You may add more features if you like.)*  

## ⌨️ Planned Inputs and Outputs  

- **Inputs**  
  student ID, student name, dates

- **Outputs**  
  dates tardy, absent, present, or cutting classes

## 🧠 Logic Plan  
Describe your program’s logic:   The logic pulls raw student records apart from helper functions so that the data also remains untouched while turning text statuses into insights. First the text statuses into numeric credit. Second, the logic checks every entry against an allowed list to catch typos early. It then tracks the student data into a single-day class roll call.

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
