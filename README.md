# subkiller-v2

My solution for Chapter 6 Exercise 6 of “Introduction to Programming Using Java”.
Implementation note: This exercise was an update of the textbook author's Subkiller.java class.
I added instance variables for hits and misses, incrementors for them, and updates to the draw()
method to draw the variables as text.


NOTE: This is a javafx program. It requires the javafx library as a dependency. (See bottom of this README for javafx instructions).

Problem Description:
For this exercise, you should modify the SubKiller game from Subsection 6.3.6. You can
start with the existing source code, from the file SubKiller.java. Modify the game so it
keeps track of the number of hits and misses and displays these quantities. That is, every
time the depth charge blows up the sub, the number of hits goes up by one. Every time
the depth charge falls off the bottom of the screen without hitting the sub, the number of
misses goes up by one. There is room at the top of the canvas to display these numbers.
To do this exercise, you only have to add a half-dozen lines to the source code. But you
have to figure out what they are and where to add them. To do this, you’ll have to read
the source code closely enough to understand how it works.

Javafx setup instructions:
Download javafx from: https://gluonhq.com/products/javafx/ (I used javafx 12). Save it to a location of your choice.
Unpack the zip folder.
Open my project with your IDE of choice (I use intellij IDEA).
Add the javafx/lib folder as an external library for the project. For intellij, this means going to "project structure" -> "libraries" -> "add library" ->{javafx location}/lib
Add the following as a VM argument for the project: --module-path "{full path to your javafx/lib folder}" --add-modules javafx.controls,javafx.fxml,javafx.base,javafx.graphics,javafx.media,javafx.swing,javafx.web
Build and run the project as normal.
