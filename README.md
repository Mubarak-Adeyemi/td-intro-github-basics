1. What do you understand by Git?

Git is a distributed version control system that is open source and was developed by Linus Torvald in 2005. Git offers data assurance to allow distributed non-linear workflow with the high quality software development. It is regarded as the gold (mothern) standard for software development and the most extensively used control system.

Git features the following:
    1.  Free
    2.  Open source
    3.  Scalable
    4.  Super fast
    5.  Cheap branching and merging.



2. Define Version Control

Version Control System tracks and manage changes whenever we write new codes or take further action while writing codes.

Benefits of VCS are as follows:
    1.  With lesser or larger projects, it aid the development team to work more     quickly and efficiently.
    2.  It facilitate the DevOps team in timely product release and strees-free deployment.
    3.  It protect source code against catastrophes as well as the casual occurrence of human unforseen consequences.
    4.  It keep tracks of modification in a specific type of database.

Features of a good VCS:
    1.  It should supports developer's workflow.
    2.  It should work on any plaform.
    3.  It fcilitate a smooth and continuous changes to the code.


3. Describe the process of committing a project to github repository

    *   Creating a folder on the local machine and a new project on github account (both should be named indentically).
    *   After adding the necessary files to the local folder then on the terminal (mac)/command prompt(windows) or VS Code's terminal we're going to navigate to the folder and initialize it with the command 'git init' (after the git software is installed on windows ).
    *   Adding or staging our the files/changes with the command 'git add .'.
    *   Commiting what we have added to our local git repository with the command 'git commit -m "first commit"'.
    *   Setting the branch name with the command 'git branch -M main'.
    *   Linking the local repository with the remote repository 'git remote add origin https://github.com/acountName/folderName.git'.
    *   Pushing the project with the command 'git push -u origin main'.