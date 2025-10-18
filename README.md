# Web-Demo
This is a demo repo for Git &amp; Github, for Web development.
//For setting configuration:
---> git config --global user.name "Your Name"
---> git config --global user.email "someone@gmail.com"
# File status Life Cycle:
Untracked(newFiles)->(add)->Unmodified(changesFile)->(add)->Modified->(makeChanges)->Staged(i.e.now "add").
# Process of commiting change:
-> add - adds new/changed files to git staging area;
        git add <-file name-> or git add . (for all at once)
-> commit - git commit -m "some message"
-> push - upload local repo to remote repo
        git push origin main
# Basic git commands:
for cloning repo: git clone "https url of repo".
for chechking status: git status