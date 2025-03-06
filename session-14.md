How we develop code locally ? Where do we publish it ?

GIT: Client based verison control system installed on computer or server

GitHub / GitLab / BitBucket: Centralized Version Control System

Git Flow
Computer to GitHub Authentication

If you're using Windows:
    1) GITBASH ( Install GitBash, this offers Git Client and terminal )
       > Click on windows button, click Git Bash and this opens the terminal for you.
    2) VS Code
        > Download and install it, once it's installed, just click on VSCode to open.

If you're using MacBook / Linux:
    1) Just install git ( Open your terminal : "$ brew install git" )
    2) Install VSCode for Mac

Once you install the VSCode, make sure to enable the "AUTO SAVE Option" on FILE and this saves all changes automatically.

GitHub Action is the CI/CD Framework which can learnt for free on GitHub, if your repositories are under an ORG and they are free.


Understand these terms:
    $ git clone repoName : This means downloading the whole repo to your local ( If the repo is public , it won't challenges with userName and password )
    $ git push : Once you made a clone, if you made some changes, we publish those changes back to the central repo 
    $ git pull : If there are some changes on the git repo, to download those changes, we use "git pull" 
    $ git commit -m "Standard Msg" : This is to give some message to the changes that you make 

# Wheneven want to push your changes, here are the steps to be followed 

    1) git add fileName-that's-changes or simply "git add ." this includes all the files in your directory
    2) git commit -m "EXP-APP-7: Updated the session-14 file"
    3) git push