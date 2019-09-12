# example_repo

This repo is an example from data science I on sept12 2019

How to start a project on R first then go to github: 

New workflow – Project first
The “GitHub first” workflow works well, but it’s not the only way to add version control to an R Project. An alternative is “Project first”:

Create an R Project with a reasonable name and path (via usethis::create_project())
Turn on version control for the project using git (via usethis::use_git())
Optionally, create remote repository (via usethis::use_github())
Keep everything related to the analysis – data inputs, scripts, reports, output – in the directory, and use R Markdown as much as possible
Keep track of changes using version control (save, commit, push)
Periodically check for reproducibility of the analysis