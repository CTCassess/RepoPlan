## Workplan for repository development

* what code we wish to store as projects (repositories)
* best structure and appropriate documentation for each project
	+ for R code, the order from most to least desirable:
	    + an R package, with user-accessible functions having help files including example application of each function, and a vignette
	    + R files with all critical code wrapped inside functions (such that sourcing the file won't result in any code execution. Example script demonstrating function application, markdown or text file explaining application
	    + R scripts, with documentation
	 + MS Word & Excel files are a poor format to share on git due to its inability to read for file changes. Text files (preferably in markdown) might be the best format choice.
	     
* identify each person responsible to push particular code (which may not be the most recent version, but the last agreed-upon working version).
* Set timelines that each project should be established on host server.

<!--- this is a comment --->

| Project | Responsible Individual  | Upload Date | Details|
| :---    |     :---     |   :--- |    :--- |
| RepoPlan  | Folkes   | Jan 25, 2019   | multiple .md files defining repository workplan. easy migration |
| ctctools  | Folkes   | Jan 31, 2019   | R package on github, easy migration |
| DGM | Wor | Jan 31, 2019 | workplan and model questions as md files. no code |
| ERAR | Wor  | Jan 31, 2019   | R code in multile .R files. Not a package |
| Annual reporting .rmd  |    |    |



This is a table template:

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
