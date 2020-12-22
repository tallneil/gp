# GP
A daily planner in Sublime Text using custom syntax highlighting.

### Background
GP is short for gameplan. Throughout college, I used a .txt file in Sublime as my daily planner. This repo includes an example and the file I wrote for custom syntax highlighting. My main goal was to keep track of assignments and scheduled events in the same place. And, I wanted to easily move uncompleted tasks from one day to the next.

### Syntax highlighting
After using plain text formatting for a while, I wanted a way to call out dates, times, and pressing assignments with more prominence. When I first wrote the file for custom syntax highlighting in June 2016, the workflow was a bit different, and involved creating a TextMate file (.YAML-tmLanguage). Since then, Sublime has updated the flow, and now accepts .sublime-syntax files. I've included both files in the syntax directory.

To save the .sublime-syntax file, go to Tools > Developer > New Syntax and copy/paste in the file I've provided. Save it in the default location. Now, when you open/reopen any .txt file, you'll see GP in the language list. 

### References
[https://www.sublimetext.com/docs/syntax.html#include-syntax] 
(Sublime Text new syntax definitions)

[https://macromates.com/manual/en/language_grammars#naming_conventions]
(TextMate naming conventions)

[https://stackoverflow.com/questions/49781644/custom-syntax-in-sublime-text-3]
(Useful instructions on StackOverflow)