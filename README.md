# GP
A daily planner in Sublime Text using custom syntax highlighting.

![Screenshot of gp.txt](/screenshots/screen_01.png)

### Background
GP is short for gameplan. Throughout college, I used a .txt file in Sublime as my daily planner. This repo includes an example and the file I wrote for custom syntax highlighting. 

Goals: 
+ Keep track of assignments and scheduled events in the same place (hybrid todo list + calendar)
+ Easily move uncompleted tasks from one day to the next

### Syntax highlighting
After using plain text formatting for a while, I wanted a way to call out dates, times, and pressing assignments with more prominence. When I first wrote the file for custom syntax highlighting in June 2016, the workflow was a bit different, and involved creating a TextMate file (.YAML-tmLanguage). Since then, Sublime has updated the flow, and now accepts .sublime-syntax files. I've included both files in the syntax directory.

To save the .sublime-syntax file, go to Tools > Developer > New Syntax and copy/paste in the file I've provided. Save it in the default location. Now, when you open/reopen any .txt file, you'll see GP in the language list. 

![Screenshot of the language list](/screenshots/screen_02.png)

### References
[Sublime Text new syntax definitions](https://www.sublimetext.com/docs/syntax.html#include-syntax)

[TextMate scope/name conventions](https://macromates.com/manual/en/language_grammars#naming_conventions)

[Useful instructions on StackOverflow](https://stackoverflow.com/questions/49781644/custom-syntax-in-sublime-text-3)