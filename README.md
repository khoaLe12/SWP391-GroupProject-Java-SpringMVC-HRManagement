# E-Recruiment - Java Web-based Project
This is a group project of the subject SWP391 of the 5th term at FPT University. The goal of the project is to develop a web application to be used for managing the online recruitment process
## Members:
* Lê Đăng Khoa  - <a href="https://github.com/khoaLe12">GitHub</a>
* Nguyễn Đức Toàn - <a href="https://github.com/Toannd832">GitHub</a>
* Lồ Quang Thắng  - <a href="https://github.com/Quang-Thang">GitHub</a>
* Trần Võ Hoàng Trọng Ân  - <a href="https://github.com/JTRerer">GitHub</a>
* Lê Quang Phú -  <a href="https://github.com/Minstreal1">GitHub</a>
## Tech Stack
**Build tool:** Maven

**Front-end:** HTML/CSS, JavaScript

**Back-end:** Spring Web MVC, Spring Security, Hibernate and JPA, Criteria query API, Google Authentication(OAuth2), SQL Server
# Description
This web application is developed for 5 user roles including Department, Candidate, HR Employee, Interviewer, HR Manager. Role department can login using email and password, the rest of roles can login with google as provider and there are 2 sections of login google (1 for candidates, 1 for employees). If candidate is a new account, system will automatically add new account to database.

## The Recruitment Process: 
* Post job vacancies -> Applying Job -> Evaluating CV(Pass/Fail) -> Schedule an interview -> Make reports of candidates -> Final Decision(Pass/Fail)

If CV fail, candidate will fail the job that he/she applied. If CV passed, candidate will get a interviewer schedule. 

Candidate or interviewer can reject their schedule but they have to write reasons for that rejection. 

After each Interview schedule, interviewers need to write reports for each candidates. HR Manager will base on that to give a final decision.

## Business Rules:
The maximum number of candidates of a interview schedule is 10.

## Roles and features
* Department: Manage job postings (View/Create/Delete)
* Candidate: View Job Postings/Post Details, Apply job, View job applications, View schedules, Accepct/Deny interview schedule, ...
* HR Employee: Manage job postings (View/Accept,Deny/End), Manage job application(Evaluate CV, schedule,...), Manage interview schedule(Create,Start,...)
* Interviewer: Manage schedule (Accepct,Deny,End), Manage Report(Write/Edit Reports)
* HR Manager: View job applications, Make a final decisions(based on CV,reports)

## File Structure
We build this web app following 3 layer achirtechture 

![File Structure](https://github.com/khoaLe12/java-swp391-HRManagement/blob/main/Pictures/Screenshot%202023-04-17%20163330.png)
