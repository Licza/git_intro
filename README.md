# Intro to Git
This is me chnanging the readme. !!!!!!
This repository is meant to be a gentle introduction to github.  We will work through the process of creating and cloning a repository, committing changes, forking and merging.  For more in depth commentary see STOR 390 (Moral Machine Learning) course notes. 

This ReadMe should serve as the elevator pitch and user manual for your repository.  Any other software packages or installations that are necessary to run the included code should be listed here.  Data sets should be mentioned and cross-referrenced here.  

Notice that there is a syntax of sorts to writing within this ReadMe.  We are using *Markdown* syntax which should be reminescent of RMarkdown.  We can offset sections, *italicize*, **boldface**, create formlas ($x^2+y^2=z^2$), etc.  

## Software

Our class will be using R for computation.  
For Windows: [https://cran.r-project.org/bin/windows/base/]  
For Mac: [https://cran.r-project.org/bin/macosx/] 

Though we will be working in R in this course, realize that github is capable of maintaining a repository with multiple coding languages simultaneously.  To illustrate this, I have also included a matlab .m file.  Howevever, we should not (in general)[^1] expect these files to interact effectively with one another.  

## Branches

There are three branches currently in this repository.  The `main` is the primary devolopmental pathway.  `Student_correction` hosts a student exercise on forking, and protects the main against the intentional error in the corrupted file.  `atacker22dw-patch-1` illustrates the utility of a branch and pull request.  

## Forking 

When forking, make sure to fork all available branches.  This will allow you to change files on non-protected branches and push them to the `main`.  

## Merge Conflicts

This branch is meant to illustrate merge conflicts and how so-called linear editing can help avoid such conflicts.  Fork this branch, edit it in some way.  For sake of argument, just remove the following parethetical (Andy is so awesome).  After you have forked this branch, I will commit to an edit as well.  When you create a pull request, I will not be able to directly merge your edit to this branch because it will be both one commit ahead and behind the current branch.  Github does not know how to (automatically) merge branches in this case.  

[^1]: It is possible to use R libraries to read in .mat files and vice versa.
