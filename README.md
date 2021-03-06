# GIT Basics

## Local

- `git init`: create git repository in current folder.
	- you only do this one per repository.
	- do not nest git repositories.
- `git status`: shows you a status of any commits within the repo; 
		version control; shows who did what.
- `git add <files>`: when written before a filename, it will put you in
		the staging area (index).
- `git commit`: when saving to the master or main branch, 
		you write what changes you did in order for
	        others to follow. The file merges into master or main.
	- `git commit -m "MESSAGE"`: oneline commit message without 
- `git log`: show you your log history
	- `git log --oneline`: one line version of your history.

- `git diff`: will show you the differences
	- `git diff --staged`: show you the differences between stages.
	- `git diff HEAD~2`: diff 2 places back from HEAD
	- `git diff <HASH>`: diff 2 locations
- `git checkout <HASH> <FILE>`: revert file
- `git checkout <HASH>`: go to location
- `git checkout master`: go back to master

## Remotes

- `git remote add origin <URL>`: adds the url with the name "origin"

- `git push origin master`: sends master branch on local computer 
- `git pull origin master`: updates local with remote (master)
- lets delete this last input cuz its not important and we are learning 
	how to revert things
