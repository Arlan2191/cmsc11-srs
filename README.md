# cmsc11-srs
This is just a simple C implementation of a Student Registration System using only stdio.h as header with my own defined functions and structs. This is a simple project I would like to share to everyone. There are sample .txt files for the Reading Function, SUBS.txt for the subject record, and SRS.txt for the student record.

Defined Structs:
Subject - includes the subject ID, subject code, and subject title
Student - includes the student ID, first name, last name, section, 3 exam scores, 3 subject pointers, a total of the test scores and their grade
Statistics - inlcludes the lowest score, highest score, average, and standard deviation

Defined Non-Void Functions:
Strcspn, ToInteger, Strcmp, ToLower, ToUpper, Strcmp, Strcat, Strcpy, Sqrt. These functions are my implementations of the built-in functions with the same name and functionality in C.

These Student Registration System allows users to do the following:
1.) Create Student
      > This part basically prompts the user to create a student record(s---)
      > This function also is divided into two, wherein the user may prompt to enroll a 
        student [manually] or through a [.csv] or [.txt] 
  
2.) Update Student Record
      > This lets the user update / edit any existing student record
      > 3.) Dropping Subjects
            > In any case the user wants a student to drop from a subject he/she is 
              enrolled
              
4.) Display Student Records
    > This allows the user to display all existing student records
    > 5.) Search Student Record
          > The user is also able to search for a specific student student record
          
6.) Delete Student Record
    > This allows the user to delete a specific student record while
    > 7.) The user is also able to delete ALL existing student record

8.) Statistics
    > From the inputted data (scores) of students, statistics are displayed accordingly
      with [min], [max], [average] values from all data records.
      
9.) Export Student Record
    > The user is also able to export all existing student record to a [.csv] file
    
10++) Subject Functions
    > Create Subject - The user is able to create certain subject records wherein
      a student may be able to enroll to.
      > The user may do this [manual] and or through a [file]
      
    > Edit Subject - The user may edit certain information of subject with this that
      will automatically be seen when using the display function
      
    > Search Subject - The user is able to search for a specific subject and be prompted
      to certain functions they wish to do
      
    > Delete Subject - The user is able to delete a subject 
    
    > Export Subject - The user is able to export all the subject records to a .csv file
