you have to write 

step.1:
	git init 

step.2: 
	git status 
this step check what files unadd into the staging area
if not, you would see the filename with red 

step.3: 
	git add filenames
this step add the file into the staging area

Again you can use "git status to check what file store in the staging area
if yes, you would see the filename with green

step.4:
	git commit 
	
Ok, you would add the file into the repository
There are some problems when I would like to code git commit

Step.5:
	you can compare the modified version and original version 
	use
	" git diff" 
Step.6: 
	you can see who, when, what change the file 
	use " git log" 
Step.7: 
	git checkout "branch_name"
	let you chenge the branch
step.8:
	git branch
	let you know which branch you are 
stpe.9:
	now you can choose the branch you would like to update to remote repository 
	if you open the new repository, you must code the website on the github

	git remote add origin https://github.com/Li-158/the-test.git ( or git remote add origin "URL")

	to let the computer know where you put the file

	Following, you upload the file into where the link is 
	git push -u origin main	(or git push -u origin "branch_name) 
	
	You can see more information on the following links,
	https://medium.com/@brad61517/git101-%E5%BF%83%E5%BE%97-%E7%AD%86%E8%A8%98-github-%E6%93%8D%E4%BD%9C-push-pull-clone-fork-a414d4af64be

	here is some diff between "push" and "pull"


