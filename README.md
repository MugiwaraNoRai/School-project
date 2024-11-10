This project reperesent a school/university system usging javafx/maven/ in intellij and MySQL as Data Base
the project is server client based: where any one should register except for the master (he sign in) . and after register , they have to sign in
each time they wanna use the client . 

there is a 3 type of clients :
1)Head Master : Master can see all the data about student's including courses analysis , data collection .
all lecterurs extra time requests run by him with the reason for it , he can accept or decline the teacher request for extra time on the live exam ,
when he accept all the time for the students doing exam's is added.
2)Lecturer: Lecturer should register , and mark all the courses he can teach . (id is checked so there is no 2 id's is similar)
he can create questions and add them to the exams questions Archive in evert course he teach .
he can create exam , choose all the qeustions he wants from the archive,
he choose exam time ,exam id ,and create a code to pass it to the students so they can inter the exam.
there is 2 ways student can do exam :
    1)online where the exam is American (student choose the Right answer) 
      in this way , the mark of student is set automatically
      teacher can still change the grade , see all the students answer , and can write notes to the student.
    2)Download the exam : 
      here , evert student dwonload his exam , solve it and upload it .
      teacher will check his exam and put the grade and can add notes to each questions.
      in both ways , when the time for the exam is done . exam stop automatically , and the answers thats he had will be saved and checked
      automatically or by the teacher depends on how he did the exam(online or downloaded it)
      Teacher can see all the data of the courses he teacged such as : AVG , highest grade , lowest , etc..
      Teacher can ask for extra time to the students , he picks the time he wants and wait for manager approval.
3)Student: Student should register to the system , pick the courses he wanna learn , pick the lecturer . (id is checked so there is no 2 id's is similar)
student can start exam , see his marks . his exam notes and his answers .
when he start exam he have to pick the course , exam id , and enter exam pw that he got from teacher inorder to start exam.
when exam start his time starts , he can pick between doing it online or download , and when he finish he just press submit and his exam is uploaded.

