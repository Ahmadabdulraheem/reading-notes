Reflection and Discussion
---

# GIT INTRO
1. ### INTRODUCTION
 **Git* is an open-source version control system. It was designed and developed by Linus Torvalds (creator of the Linux kernel) and is the most popular version control system to date.

2. ### BENIFITS 
    There are several reasons to use Git (or version control in general). We will just list a few reasons:

*Git helps out a lot with respect to incremental code development and documentation.
*Git is relatively easy to pick up and learn.
*Git is very efficient and will not adversely affect your code.
*If you make a mistake with your code, Git can easily revert you back to a working version of your code.
*You can easily maintain multiple backups of your code that can update themselves without you needing to copy/paste your code over.
*You can review the history of your code.
*You can make multiple versions of your code.
*You can work on experimental changes or features without breaking your working code.
*You can keep track of contributions to the code when working as part of a team.
*Companies use version control, so you will need to learn version control eventually.

3. ### HOW ITS WORK
  * **Tracking and Staging a New File**
    $ git add *

  * **Committing a File**
After staging one or multiple files, you should commit the changes and record what you did within the commit message:

$ git commit -m “made change x,y,z”

  * **Pushing Changes**
Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.

$ git push origin main
