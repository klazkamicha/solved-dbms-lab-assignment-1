Download Link: https://assignmentchef.com/product/solved-dbms-lab-assignment-1
<br>
<strong>Objective: To learn SQL for creating and retrieving information from databases  </strong>

<ol>

 <li>Create a database for University placement system with following relations:</li>

</ol>

Student(sroll, sname, gender, branch, programme, CGPA)

Company(company_id, name, specification)

Interview(sroll, company_id, idate)

Offer(sroll, company_id, osalary)

Create primary keys and foreign keys in each relation. Insert suitable records in all relations. A student can receive at most 3 offers.

Write SQL Queries for the following(s):

<ol>

 <li>List all students name and their branches who have received at least one offer.</li>

 <li>List all students name who have received offer with salary &gt;100k.</li>

 <li>List the students who has appeared in at least one interview but didn’t receive any offer.</li>

 <li>List the name of MTech students who have received at least one offer.</li>

 <li>List the name of girl students who have received at least one offer.</li>

 <li>List branch-wise number of offers received.</li>

 <li>List the name of the students who have received maximum offered salary.</li>

 <li>List the branchwise name of students who have received maximum offered salary.</li>

 <li>List the name of the branch which has received maximum number of offers.</li>

 <li>List the number of students in each branch who have not received offer.</li>

 <li>List the student wise offer details with following fields &lt;Student Name, Gender, Branch, Company Name, Specification, Osalary&gt;</li>

</ol>




<ol start="2">

 <li>Design a university database with following details. Insert few more records in the database with the given relational schema. The Major and Department attributes can take values “CS”, “ECE”, “EE”, “MATH”. The Grade can take values “A”, “B”, “C”, “D”, “P”, “F”. Create primary keys and foreign keys for different relations as per the content of the database.</li>

</ol>




Write SQL queries for the following(s):

<ol>

 <li>Create transcript for each student with &lt;student name, course number, semester, year, section_id, grade&gt; ii. Display name of the students who has received A grade in all the courses registered.</li>

</ol>

<ul>

 <li>List the number of students registered in each course.</li>

</ul>

<ol>

 <li>List the name of students who have registered for all the courses instructed by “Anderson”.</li>

 <li>Display the student wise total_credit taken in a given year. Year should be provided as input by user.</li>

 <li>List the name of the students who has registered for at least one MATH course and 2 CS courses.</li>

</ol>

<ul>

 <li>Delete records for the course MATH2410 from course relation. The referenced records in section, grade_report and prerequisite relations must be automatically deleted.</li>

</ul>

vii. List the name of the students who has received more than one F in a given semester. Semester would be given as input.  viii. Update Grade attribute values in Grade_Report relation with following rules: A – 10; B – 9; C – 8; D – 7; P – 6; F – 5


