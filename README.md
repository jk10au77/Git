# Git
We will learn Basics of Git

About Git:
---------------
a. Git is a Version control system that tracks changes in files 
b. It is mainly useful when a group of people are working collaboratively on a project
c. Using Git, we typically do the following tasks
    1. Create a branch: create a branch off from the main copy of files that your group of people working on
    2. Make edits: edit files independently and safely on your own personal branch
    3. Merge: It merges your specific changes back into the main copy of files, so that your changes don't impact other people's updates.
    4. keeps tracks of your changes and other people's changes, so you all stay working on the most up-to-date version of the project.

Git can be learned in two ways.
  a. using command line version
  b. using Graphical User Interface (GUI) version.

------------------------------
Version Control System (VCS):
------------------------------
  a. It tracks the history of changes 
  b. We can recover earlier version of the project if required.
  c. Developers can perform the following tasks
      1. Which changes were made?
      2. When those changes were made
      3. Who made those changes.
      4. Why were they made?

-------------------
Setting up Git:
-------------------
link: https://docs.github.com/en/get-started/git-basics/set-up-git

  a. Download and install the latest version of Git
  b. Set your user name in Git
  c. Set your commit email address in Git

  b. Set your user name in Git:
  --------------------------------
    a. Git uses user name to associate commits with identity. The git user name is not same as your GitHub username

    Git USERNAME:
    ----------------
      1. using 'git config' command, we can change the name that is associated with your Git commits

        Using the below command, you can view all your settings and where they are comming from

            git config --list --show-origin

    -----------------------------------------------------------
    Setting Username for every repository on your computer:
    -----------------------------------------------------------
    a. Open Git Bash
    b. Set a Git username using the below command.
            git config --global user.name "Mona Lisa"
    c. Confirm that you have set the Git username correctly:
            $ git config --global user.name "jk10au77"
    d. Confirm that you have set the Git username correctly:
            $  git config --global user.name

    Note: You can set user name to a single repository. To do so, first change the working directory where the repository resides. Then do the above steps.
    
    ---------------------------------------------------------------
    Setting email address for every repository on your computer.
    ---------------------------------------------------------------
        a. Open Git Bash
        b. Set an email address in Git using the below command
                $ git config --global user.email "YOUR_EMAIL"
                example: git config --global user.email "tatiparthi.jaya@outlook.com"
    
    --------------------------
    Checking your setting:
    --------------------------
    using the below command. check your Git setting
            $ git config --list


    
                
