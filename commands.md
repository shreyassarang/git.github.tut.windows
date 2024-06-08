Git

Git version:
```git --version ```

	Configuring git
```
git config --global user.name "<name>"

git config --global user.email "<email>"

git config --list
 ```

cloning a repo:
```git clone <-link->  ```

status of all the files of a repo
```git status  ```

	Four types of status:
1. untracked : newly created
2. modified : changed
3. staged : ready to committed 
4. unmodified : unchanged

Adding new and other modified files to git staging area
```git add <file name>```

To add all the files at once
```git add . ```

Committing the changes made in repository
```git commit -m "<message>"```

Updating github repo:
```git push origin main```
origin : the repo from where we cloned the repo
main: branch to where we need to update

Creating a repo on local system and then making repo on Github:
Skip the cloning part and do the rest steps.
Create a new repo and for connecing the git to that repo, use the following command.

Common command:
	ls : list out all the files
	ls -a: listing hidden files
	cd : change directory
    cd .. : backspace to previous folder