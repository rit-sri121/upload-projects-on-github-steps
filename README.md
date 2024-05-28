First thing first you need to open the github account 
Make a new reporesitory with some unique name "New-practice-repo"
while creating do some changes within new repo like making it visible to public.
Open your local CMD.
Go to the folder where you have created your new folder where project exist.
Copy that path and type in cmd = cd \Users\ritsr\OneDrive\Documents\Desktop\DEbootcampAWS or cd <path of the folder>
now initialize git on the same folder by =git init
once initialized it will show message like the screenshot attached in another file.
Now you have to add the chnages that you make like here we are adding our projects in github so = git add .
Make a commit with message = cd commit -m "I uploaded one project here"
check your changes made correctly by = git status
In step 11 all should be green showing the current changes in specific folders.
Now after commiting make all changes to push in master branch which is your repo newly created by you in github.
So add it remotely the branch url by git remote add origin <url>
then the last ever step you have to just make it push to the main branch 
type = git push origin master
YOU ARE GOOD TO GO!!!
