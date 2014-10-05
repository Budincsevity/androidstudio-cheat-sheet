Android Studio Cheat Sheet
=========================

Collection of the best Android Studio tips and tricks. 
Based on the [Android Developer Tools](https://plus.google.com/u/0/communities/114791428968349268860) circle daily tips. 

##Analyze Data flow to Here
This will take the current variable, parameter or field and show you the path it has taken to get here!
This is very useful when you are entering an unfamiliar place in the code base and you want to understand how this parameter got there.
- Menu: Analyze → Analyze Data Flow to Here
- Find action: Analyze Data Flow to Here

![My image](https://lh4.googleusercontent.com/-Fv4MxHWIdHw/VCFWY4Ykv0I/AAAAAAAANoQ/YVe2hmnkAPE/w667-h348-no/31-analyzedataflow.gif)

##Compare With Clipboard
This will take the current selection and do a diff with the content of your clipboard.

Shortcut:
- Mouse: right-click the selection and select Compare With Clipboard
- Find action: compare with clipboard
 
![My image](https://lh6.googleusercontent.com/-6rDn8kL7Pgw/VClEM13oYKI/AAAAAAAAN0o/JWiduW1pWsU/w519-h265-no/34-comparewithclipboard.gif)

##Compare With Branch (Git)
Assuming that your project is under Git, you can compare the current file or folder with another branch.
Pretty useful to get an idea of how much you have diverged from your main branch.

Shortcut:
- Menu : VCS -> Git -> Compare With Branch
- Find Actions: Compare With Branch﻿

![My image](https://lh6.googleusercontent.com/-xW1J3BBZHZc/VC6FVCMexWI/AAAAAAAAN8M/GEJqszoqzXk/w570-h328-no/38-comparewithbranch.gif)

##Postfix Completion
You can think of it as a code completion that will generate code before the dot instead of after it. In fact, you invoke it just like a regular code completion: you type a dot after an expression.

E.g. to iterate a list, you could go "myList.for", press tab and it would generate the for loop for you.

You can get a list of what you can type by typing a dot after a statement and looking at the postfix keywords that come right after the regular code completion keywords. There is also a list of all available keywords in Editor → Postfix Completion

Some of my personal favorites:
- .for (for a foreach)
- .format (wraps a string in String.format())
- .cast (wraps an expression in a type cast)

![My image](https://lh5.googleusercontent.com/-rLMdeb9cbBM/VCVUw0Y656I/AAAAAAAANt8/J2KiRPMjRzs/w474-h136-no/33-postfixcompletion.gif)
