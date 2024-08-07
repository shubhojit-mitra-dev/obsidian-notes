🎓  Course: [[DBMS LAB]]

📖  Topic: #Introduction 

📆  Date: 2024-08-05

🏷️  Labels: #tables #primarykey #introduction #lecture1 

🔗  Important Links: 

---

##### Create a Database for University to keep track of each student's, Name, Number, AADHAR,  Current and Permanent address, Contact details of person and parents, DOB, sex, Branch, Specialization major and minor.

##### Course name, Course Code, Course description, Number of lecture hours, Course Level, course dept.

##### Dept name, dept code, dept contact number, dept mail ID, number of faculties in dept.


## Database: University

#### Table: Personal Details (Primary Key: Social Security Number)

| Social Security Number | Student Name    | Student contact number | Parent Contact number | Current and Permanent Address | Sex  | DOB        | Branch | Specialization (Major) | Specialization (Minor) |
| ---------------------- | --------------- | ---------------------- | --------------------- | ----------------------------- | ---- | ---------- | ------ | ---------------------- | ---------------------- |
| 2107927                | Shubhojit Mitra | 9284726743             | 2747283728            | A98 ABC street, Kanpur        | Male | 10-11-2005 | SoCS   | N/A                    | N/A                    |

#### Table: Courses (Primary Key: Course Code)

| Course Code | Course  name      | Course level | Number of lecture hours | Course dept | Course description                                                                   |
| ----------- | ----------------- | ------------ | ----------------------- | ----------- | ------------------------------------------------------------------------------------ |
| CSEG_2933   | DBMS              | UG           | 60                      | SoCS        | A comprehensive course on Database Management System                                 |
| CSAI_2944   | Elements of AI/ML | UG           | 60                      | SoCS        | An introductory course on principles of Artificial Intelligence and Machine Learning |

#### Table: Departments (Primary Key: Dept Code)

| Dept Code | Dept Name                      | Dept contact | Dept mail ID                           | Number of faculties |
| --------- | ------------------------------ | ------------ | -------------------------------------- | ------------------- |
| SoAE_2938 | School of Advanced Engineering | 2947248262   | schoolofadvancedengineering@upes.ac.in | 657                 |
