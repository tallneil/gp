# GP
A daily planner in Sublime Text using custom syntax highlighting.

![Screenshot of gp.txt](/screenshots/screen_01.png)

### Background
GP is short for gameplan. Throughout college, I used a .txt file in Sublime as my daily planner. This repo includes an example gp.txt (from March 2017), and instructions on custom syntax highlighting. 

My goals for GP: 
+ Keep track of assignments and scheduled events in the same place (hybrid todo list + calendar)
+ Easily move uncompleted tasks from one day to the next
+ Scan to see upcoming assignment due dates and exam dates

### Syntax highlighting
After using plain text formatting for a while, I wanted a way to call out dates, times, and pressing assignments with more visual emphasis. When I first wrote the file for custom syntax highlighting in June 2016, the workflow was a bit different, and involved creating a TextMate file (.YAML-tmLanguage). Since then, Sublime has updated the workflow, and now accepts .sublime-syntax files. I've included both files in the /syntax directory.

To save the .sublime-syntax file, go to Tools > Developer > New Syntax and copy/paste in the file I've provided. Save it in the default location. Now, when you open/reopen any .txt file, you'll see GP in the language list. 

![Screenshot of the language list](/screenshots/screen_02.png)

### Manual updates
Every few months, I would have to go through and fill in all the dates, assignments, scheduled meetings, etc. for the upcoming months. This was always tedious and I considered writing a script to automate the process, but I never did.

### References
[Sublime Text new syntax definitions](https://www.sublimetext.com/docs/syntax.html#include-syntax)

[TextMate scope/name conventions](https://macromates.com/manual/en/language_grammars#naming_conventions)

[Useful instructions on StackOverflow](https://stackoverflow.com/questions/49781644/custom-syntax-in-sublime-text-3)