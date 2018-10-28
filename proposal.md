# X-Team 20 Project Proposal: Grade Helper

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

We are solving the problem of difficulty calculating final grades. This program will allow teachers and students to track students grades and recieve their final score. Teachers will be able to add assignments of different weight and give each student a score. This score will be used in the calculation of the final grade.

Our program will use a hashtable with linked lists as the buckets to store the students and their grades. Each node in the hash table will reference a student which will contain fields for their name, email, a reference to assignement nodes, and a reference to their final grade. 

## Questions to answer for Exercise #2

#### 1. Name: Give your project proposal a name (and edit the top line of this file)

Grade Helper


#### 2. Output: Describe the output your program will produce.  Include an example format of the output produced.

Our output will depend on what the user asks for. There will be different options for teachers and students, with different accesses. The output options will include: seeing student information for a single student (name, email, individual grades on assignments, total grade for the class), seeing total student averages for a single assignment, seeing total student averages for a semester.


#### 3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

Student: none, all the input will be done by the teacher

Teacher: can input new student, students' individual grades on assignments, new assignments


#### 4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

> Welcome to GradeHelper
> Input User ID:
>

##### Case Student ID Entered:
> Welcome (Student Name)
>
> (Assignment One) Grade: (Assignment One Grade)
> (Assignment Two) Grade: (Assignment Two Grade)
> ...
> (Assignment n) Grade: (Assignment n Grade)
>
> Final Grade: (Final Grade)

##### Case Teacher ID Entered:
> Welcome (Teacher Name)
>
> Enter "ns" to add new student
> Enter "ea" to edit assignments
> Enter "vg" to view final grades

###### Case Teacher Enters ns:
> Enter new student's id:
>
> Enter new Student's name (lastName, firstName):
>
> Enter new Student's email:

##### Case Teacher Enters ea:
> ```
> Current Assignments:
> (Assignment One)
> (Assingment Two)
> ...
> (Assignment n)
>
> Enter r (assignment name) to remove assignment
> Enter new (assignment name) (assignment weight) to add new assignment
> Enter update (student id) (assignment name) (grade) to edit the assignment grade
> Enter average (assignment name) to display the assignment average grade
> ```

##### Case Teacher Enters vg:
> Final Grades:
> (Student One Name): (Final Grade)
> (Student Two Name): (Final Grade)
> ...
> (Student n Name): (Final Grade)

#### 5. Types List: Break your solution idea down into units that you think can be implemented with a single class.



#### Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

