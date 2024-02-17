# Instructions  
This week you will be doing a coding exercise which combines all the concepts you have seen so far in this course.

  ## Steps
  1. Create a Laptop class with attributes and methods of your choice.
  2. Create a Course class with attributes such as course ID, course name, credits and corresponding getters/setters.
  3. Create a Student class with below attributes. Ensure that you have included
     - Student name and student id
     - An Array of Courses. Every student has a list of courses. (Refer to Week 4 work for this)
     - a Laptop variable as every student is supposed to have a laptop.
     - Add an array of integers to store the score obtained by student in each course.
     - Add a static variable called *gymUsers*. This variable tracks the number of students using the gym. (Refer to Week 3 work)
     - Add a constructor that sets all the necessary variables.
     - Add a static method called *enterGym*. This method increments the *gymUsers* variable by 1. But, you must increase the count only if gymUsers is less than 10. In other words, the gym can hold only 10 members at a time. If a user is unable to enter gym, print the message:  "Please check after sometime". (Refer to Week 3 work).
     - Add a method called *validateData* that checks (Refer to Week 5 work)
       - if student name is actually a full name.
       - if student id contains exactly 10 digits
       - if all course id  are of the format - ABCD1234 (i.e.) 4 uppercase letters followed by 4 digits.
  5. In the main class,
     - Create an Array List of Students. (Refer to Week 4)
     - Add Student objects to the arraylist created above. Ensure that before adding Students, you have created necessary courses and Laptop objects to pass to Student constructor.
     - Calculate the average score all students from the arraylist.
 

  
