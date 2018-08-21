# HelloWorld
Hello World Git

Git flow:
	1. Create repo
	2. Add a file
	3. Stage a file
	4. Commit
	5. Push

Graph: 
Git log --all --decorate --online --graph

Branch: Create
Git branch <branchname>
Git branch interactive
Git branch aurora
Git branch (moves to master)

To move to branch:
Git checkout <branch-name>


Working on Branch: Checkout
	1. Checkout
		a. Git checkout <branch name>
		b. Git status

Delete branch:
git branch -d <branchname>

Git Merge:
	• Git branch -a  :lists all branches
	• Git checkout branch-a
	• Git checkout branch-b
	• Git checkout master  :to merge, should be on master
	• Git merge branch-a
	• Git merge branch-b

Tags:
To create a tag on your current branch, run this:
git tag <tagname>
If you want to include a description with your tag, add -a to create an annotated tag:
git tag <tagname> -a
This will create a local tag with the current state of the branch you are on. When pushing to your remote repo, tags are NOT included by default. You will need to explicitly say that you want to push your tags to your remote repo:
git push origin --tags
Or if you just want to push a single tag:
git push origin <tag>


	1. Checkout master
	2. Create branch A
	3. Add/modify/delete file on branch A
	4. Go to master branch,
	5. Perform merge
Git merge branch-A
