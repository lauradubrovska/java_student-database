
# The program should perform the following actions:
* Displays a menu on the screen containing five commands: Create, Calculate, View, About and Exit and enters the command number from the keyboard.
* If the user selects the Create command, the program creates a Students.dat file (in the current folder) and writes five objects of the Student class to the given file.
* If the user selects the View command, the program displays the contents of the Students.dat file on the screen.
* If the user selects the Exit command, the program ends its work.
* If the user selects the Calculate or About command, the program calls the calculate method or the about method of the Main class. The given methods do nothing.

# Task:
Modify the calculate and about methods to do the following:
* The calculate method must enter the student's number from the keyboard (assume that students are numbered from one) and modify the student's marks given in the Students.dat file. Enter new marks from the keyboard. If a negative student number was entered or the number exceeds the number of students in the file, then the program must output a "no such student" statement.
