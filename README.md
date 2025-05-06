# ECE-3574-Homework-6

Download Here: [ECE-3574 Homework 6](https://codingherolab.com/product/ece-3574-homework-6/)

For Custom/Original Work email codingprolab@gmail.com/whatsapp +1(541)423-7793

The primary learning objectives of this assignment include learning to use event-driven programming
programming abstractions including the Qt event loop, use of graphical widgets and creation of graphical
applications. Additional learning objectives include use of design patterns such as the composite pattern.
Homework:
The First Graphical Application
Write an application with four buttons (QPushButton) and a text edit box (QTextEdit) as shown in Fig 1.1

Fig 1.1 Fig 1.2 Fig 1.3
a) The first button should be labeled “Advice”. It should select a random piece of text from a file named
“advice.dat” and append the contents to the QTextEdit window as shown in Fig 1.2. The word “Advice”
should be prefixed at the beginning of the text.
b) The second button should be labeled “Weather”. It should select a random sentence about the weather
from a file named “weather.dat” and append the contents to the QTextEdit window as shown in Fig 1.3. The
word “Weather” should be prefixed at the beginning of the text.
c) The third button should be labeled “Reminder”. It should pop up a message dialog with a randomly
generated (fictitious) meeting time and descriptive message from a file named “reminder.dat” as shown in Fig
1.4
Fig 1.4

The pop-up window for the Reminder button should also have a checkbox which is marked when a message
appears. When the checkbox is not marked it should not bring up the current reminder again until the next
time the program is run. If there are no reminders that can be shown then pressing the reminder button
should instead append a message indicating that there are no more messages to the QTextEdit window as
shown in Fig 1.5.
d) The fourth button should be labeled “Quit”. It should pop up a dialog box that asks the user to respond
whether he or she really wants to quit the program. If the user selects yes, it should terminate the program.
Otherwise it should close the dialog box and return to the program, as shown in Fig 1.6.

Fig 1.5 Fig 1.6
NOTE
1. You must use signals and slots to connect the button clicks with the appropriate functions
2. You must not use the “sender” function (inside a slot) to identify the source of the signals from the button
clicks. Use the QSignalMapper instead.
3. You must not use a graphical form editor like Qt Designer for this homework. You need to write all the
code yourself.
4. The format of the files are: generally, one sentence/message per line. However, messages can span on
multiple lines by having a \ (backslash) as the last non-whitespace character on each line in the file, except
the last line. If the last line has such a backslash the error should be reported to stderr, the QTextEdit window
or via a popup window. In other words, the trailing backslash character denotes the current message
continues on the next line.
5. Pop-up windows must be modal. While a pop-up is displayed if the user presses a button in the main
window it will not affect the state of the program.
