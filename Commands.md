<h1>for windows</h1>
<ul>
        <li>ctrl + x [will exit out of the loop or frm anything]</li>
        <li>pwd will open the current working directory</li>
        <li>ls will give you list of all the folders present in the directory</li>
        <pre>
            <li>drwxr-xr-x 1 MSA 197609 0 Oct 22 23:48</li>
            first letter d stands for directory
            if the first letter is - it means it's a normal file
            next 3section stand for read, write, exicute access for the user
            ans the next 3 sections are for read , write, exicute for the group
            the next 3 are for everyone who are not the user or a group
        </pre>
        <li>cd will take you to the home dir </li>
        <li>ls -a will give you a list of all the hidden directory<li>
        <li>ls -al will give a detailed list</li>
        <li>cd (change directory) after cd when you hit tab it will auto complete for you</li>
        <li>dir (lists all the directory) </li>
    <li>cd - will take you to the previous dir which you were using</li>
    <li>cd .. will take you a step back from the curr dir</li>
    <li>cd name (will go to the floder called name) </li>
    <li>mkdir folderName (will create you a new folder with the mentioned name)</li>
    <li>touch fileName.txt (will create you a new file)</li>
    <li>cp filename.txt(currdir) folder/folder(relative path) [will copy the filename.txt to the mentioned relative path]</li>
    <li>mv filename.txt(currdir) folder/folder(relative path) [will move the filename.txt to the mentioned relative path]</li>
    <li>mv fileName.txt newFileName.txt [will rename the file to the current dir]</li>
    <li>rm fileName.txt [will remove the file]</li>
    <li>rm -r folderName [will delete the folder and files in it]</li>
    <li>nano filename.txt [will let you edit some files in the dir]</li>
    <li>cat filename.txt [will show you the text present in the file you can also add another filename it will concat the things and show the result on hte screen]</li>
    <li>cat file1.txt file2.txt > file3.txt [it will create a new file and concat the text present in both the files in one]</li>
    <li>ls > filename.txt [will take the output from ls and put it in a  new file] </li>
    <li>echo hi [will print hi on cmd]</li>
    <li>echo hi > filename.txt [will overwrite everything in file to the output hi ]</li>
    <li>echo hi >> filename.txt [will append the hi to the end of the text in file]</li>

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


