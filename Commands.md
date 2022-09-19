--> for windows
    - cd (current directory)
    - dir (lists all the directory)
    - cd .. (goes a step back)
    - cd name (will go to the floder called name)
    - git init (will initialize a git folder)
    - git status (will tell u the status of the files)
        - modified
        - staging
        - commit
    - git add nameOfTheFile (will add the file to staging area)
    - git rm --cached fileName (will remove the file from the staging area)
    - git add . (will add all the files to the staging area)
    - git commit -m "made changes to specific parts" (this will commit you work or kinda like save your progress with discription)
    - git log (will give you the whole commit history)
    - git log --oneline (will give you all your commit history in one line)
    - git checkout <id> (will give you a read only view at that timestamp )
    - git checkout master (will get you back from the previous to your main branch)
    - git revert <id> (will remove a commit but not delete it from the timeline instead it creates a new commit with diff name)
    - git reset <id> (will remove the commit from history but will retain the code in the editor just to be safe)
    - git reset <id> --hard (will remove the commit from history completly all codes after the commit will be lost)
    - git branch branchname (will create a new branch )
    - git branch -a branchName (will show me the list of all the branches present)
    - git branch -d branchName (will delete a merged branch)
    - git branch -D branchName (will delete a branch which is not merged to master)
    - git checkout -b branchName (will create a new branch and open it )
    - git merge branchName (will merge the branch to the master line )
    - git push repolink branchName (will push the master branch to the online repository on github)
    - git remote add origin https://.....com  (will create a alias called origin which you can use instead of pasting the remote link again and again)
    - git clone repolink (paste the link of a repo from github and start working on it)
    - git remote -v (will list all the alias )
    - git pull origin branchName (will fetch me all the changes that others have been made from that branch)



--> green color means they have been modified but not commited
--> staging is a extra blanket for security we can review our process
--> in commit if we want to revert back to few previous commits 
    we have few options with us 
    - checkout commit  (opens a commit you wanna look at)
    - revert commit  ()
    - reset commit (goes back to how it was at a particular time)
--> when you clone a repo from the github you don't have to setup a new alias git has already taken care of it for us
--> first you have to do git clone repolink to start working on the branch


