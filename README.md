make-activity
=============
This repository holds Caroline Seip's [hw09](http://stat545.com/Classroom/assignments/hw09/hw09.html) for [UBC STAT547M](http://stat545.com/Classroom/).

# Instructions
The purpose of this assignment was to modify a [provided pipeline](https://github.com/STAT545-UBC/make-activity) to add a new meaningful analysis using an R script, and to create an output from an R Markdown file.

# Assignment
I chose to create an [R script](https://github.com/STAT545-UBC-students/hw09-Caroline-Seip/blob/master/firstletter.R) that summarizes the number of [English words](https://github.com/STAT545-UBC-students/hw09-Caroline-Seip/blob/master/words.txt) that begin with each letter of the alphabet. I then made an output [html document](http://htmlpreview.github.io/?https://github.com/STAT545-UBC-students/hw09-Caroline-Seip/blob/master/FirstLetter.html) from an [R Markdown file](https://github.com/STAT545-UBC-students/hw09-Caroline-Seip/blob/master/FirstLetter.Rmd) that summarizes the most and least common first letters of English words, and includes a bar chart of the number of English words that start with each letter of the alphabet. 

This [Makefile](https://github.com/STAT545-UBC-students/hw09-Caroline-Seip/blob/master/Makefile) automates the pipeline to automatically run this R script and create the output .html document.

# Important files
- [Makefile](https://github.com/STAT545-UBC-students/hw09-Caroline-Seip/blob/master/Makefile)
- [R script](https://github.com/STAT545-UBC-students/hw09-Caroline-Seip/blob/master/firstletter.R)
- [Rmd](https://github.com/STAT545-UBC-students/hw09-Caroline-Seip/blob/master/FirstLetter.Rmd)
- [html document](http://htmlpreview.github.io/?https://github.com/STAT545-UBC-students/hw09-Caroline-Seip/blob/master/FirstLetter.html)
