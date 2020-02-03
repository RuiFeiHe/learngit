This is a start up for learning git.
Hello beautiful world!

Lesson 1 
use 'git add readme.txt' and 'git commit -m "..." '
---


Lesson 2
After break and return to work, use 'git status' to check if anything is changed
If somthing is changed but not added, use 'git diff'
Knowing the difference, we can then add the changed files and commit.
---


Lesson 3
To go back to previous version, use 'git reset --hard HEAR^' HEAD^^ 
To go to future version, use 'git reflog'to know the id 
    and use 'git reset --hard id'
---


lesson 4
stage and master
'git add' to put files into stage
'git commit' to move files from stage to master
---


lesson 5
retract
'git checkout -- file' to reset files in workspace to stage or master when the change is not added
'git reset HEAD file' to reset files in ws to master when changes are added to stage


lesson 6
rm
After 'rm 1.txt', use 'git rm 1.txt' and 'git commit -m "message" '
Or the delete is wrong and needed to be undo, use 'git checkout -- 1.txt'
---


lesson 7 
remote, connect to github
create a new repo on github 
'git push -u origin master' 
for every time to upload to github, use 'git push origin master'
---

lesson 8 
add a branch
'git checkout -b dev'












