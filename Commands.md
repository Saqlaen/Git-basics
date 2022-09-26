<h1>for windows</h1>
<ul>
        <li>cd (current directory) </li></li>
        <li>dir (lists all the directory) </li>
    	  <li>cd name (will go to the floder called name) </li>
    <li>git init (will initialize a git folder) </li>
    <li>git status (will tell u the status of the files) </li>
        <ul>
		<li>modified</li>
        	<li>staging</li>
        	<li>commit</li>
	  </ul>
    <li>git add nameOfTheFile (will add the file to staging area) </li>
    <li>git rm --cached fileName (will remove the file from the staging area) </li>
    <li>git add . (will add all the files to the staging area) </li>
    <li>git commit -m "made changes to specific parts" (this will commit you work or kinda like save your progress with discription) </li>
    <li>git log (will give you the whole commit history) </li>
    <li>git log --oneline (will give you all your commit history in one line) </li>
    <li>git checkout <id> (will give you a read only view at that timestamp ) </li>
    <li>git checkout master (will get you back from the previous to your main branch) </li>
    <li>git revert <id> (will remove a commit but not delete it from the timeline instead it creates a new commit with diff name) </li>
    <li>git reset <id> (will remove the commit from history but will retain the code in the editor just to be safe) </li>
    <li>git reset <id> --hard (will remove the commit from history completly all codes after the commit will be lost) </li>
    <li>git branch branchname (will create a new branch ) </li>
    <li>git branch -a branchName (will show me the list of all the branches present) </li>
    <li>git branch -d branchName (will delete a merged branch) </li>
    <li>git branch -D branchName (will delete a branch which is not merged to master) </li>
    <li>git checkout -b branchName (will create a new branch and open it ) </li>
    <li>git merge branchName (will merge the branch to the master line ) </li>
    <li>git push repolink branchName (will push the master branch to the online repository on github) </li>
    <li>git remote add origin https://.....com  (will create a alias called origin which you can use instead of pasting the remote link again and again) </li>
    <li>git clone repolink (paste the link of a repo from github and start working on it) </li>
    <li>git remote -v (will list all the alias ) </li>
    <li>git pull origin branchName (will fetch me all the changes that others have been made from that branch) </li>
</ul>
    



<li> green color means they have been modified but not commited</li>
<li> staging is a extra blanket for security we can review our process</li>
<li> in commit if we want to revert back to few previous commits </li>
    <li><h5>we have few options with us</h5> </li>
    <li>checkout commit  (opens a commit you wanna look at) </li>
    <li>revert commit  ( it will remove the changes made in this commit) </li>
    <li>reset commit (goes back to how it was at a particular time) </li>
<li> when you clone a repo from the github you don't have to setup a new alias git has already taken care of it for us first you have to do git clone repolink to start working on the branch </li>


