# StudentSkills
Work on skills
A teacher needs to insert the final score of all 9 students in class. Your task is to create a program to solve the following tasks in order.
At the beginning, you don’t need to validate any entering.
Task 1
Create a program that ask for All 9 inputs (Student score) and save it in an array.
•	Ask for 9 students score – using a loop
•	Save it in an array

studentsScore	[9]
FOR index       1 TO 9 
  INPUT Score
 studentsScore[index] 	Score
 NEXT index
ENDFOR

Task 2
After entering all 9 numbers, show a menu option in which the teacher can choose:
1.	Calculate the average
2.	Show the highest score
3.	Show the lowest score
4.	Show all scores below the average
5.	Exit
OUTPUT Choose one of the following options
OUTPUT 
1.	Calculate the average
2.	Show the highest score
3.	Show the lowest score
4.	Show all scores below the average
5.	Exit
INPUT answer
CASE OF answer
1: 

FOR index 	1 TO 9
	sum 	 studentsScore[index] + sum
	NEXT index
ENDFOR





2:
FOR index 	1 TO 9

	Highest 	0
	IF highest < studentScore[index]
	THEN
	  Highest         studentScore[index]
	ENDIF


3:

FOR index 	1 TO 9

	Highest 	0
	IF highest < studentScore[index]
	THEN
	  Highest         studentScore[index]
	ENDIF
1 2 3 6 5 1 2 3 

'A': Position ← Position – 1 
'D': Position ← Position + 1 
OTHERWISE : Beep 
ENDCASE



Output a message with the following options
1.	Calculate the average
2.	Show the highest score
3.	Show the lowest score
4.	Show all scores below the average
5.	Exit
Save it in a variable call answer
Condition with the options
If 1
Statement
If 2
Statement
If
Statement
If 4
Statement
If 5
Statement





Ask teacher to type one of the following options
OUTPUT Choose one of the following options
1.	Calculate the average
2.	Show the highest score
3.	Show the lowest score
4.	Show all scores below the average
5.	Exit
INPUT answer
CASE OF answer
1 : FOR index           1 TO 9
	sum           studentsScore[index] + sum
	average           sum / 9
       NEXT index
	//SUM studentsScore[]/9


2: highest  
	FOR index           1 TO 9


3: Position ← Position – 1 
4: Position ← Position + 1 
5:  
ENDCASE




Task 3 
The teacher has decided to increase all students score by 10%.  Modify task 1 for this purpose.
Task 4
Create validations 
1.	Minimum score 0 – maximum score 10
2.	Can only enter real number for Student score
3.	Error message on the menu option – Can only accept values 1, 2, 3 and 4. Show message errors and re-enter the values
Task 5
Before insert the score, ask for the student number, which is made of 4 digits(Integer).
Modify task 1 to ask for student number first and store it in an array.
Modify task 2 to show the student number together with the average, highest score, lowest score and students below average
You code must have appropriate comments. 
