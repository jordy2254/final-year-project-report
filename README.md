# final-year-project-report
This repo holds all the latex files for my final year project report, below is the information of the progress of the 
report, along with information on how to build it

# Project progress
References etc. are still not in place, however content is mostly there. There may be missing images too but these will 
be added at a later date.
- [x] Chapter 1
- [x] Chapter 2
- [ ] Chapter 3
    - [ ] Chapter 3.1
    - [x] Chapter 3.2
    - [x] Chapter 3.3
    - [x] Chapter 3.4
- [x] Chapter 4
- [x] Chapter 5
- [x] Chapter 6
- [x] Chapter 7
- [x] Chapter 8 (Still needs it's appendecies added)
- [ ] Chapter 9

# Building the project
The project was created with the MikTex repo on Ubuntu, to build the project run
"pdflatex -synctex=1 -interaction=nonstopmode --shell-escape project.tex"

> **_NOTE:_**  The --shell-escape is needed for the wc to automatically be placed on the title page
