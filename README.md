This is my first version code.

# Basics Git commands 

- git add "fileName" //Add the specific file
- git add . // Add all files
- git commit -m "message" // This command will create a commit... -m come from message  

~ Add repository: git remote add origin repositoryLink 

# How to make a new version?

- New code line
...
git status
git add .
git status (confirm)
git commit -m "second version - more commands"
git push

# How to view the storage versions?

- git reflog 


# Advanced Git

* How go through past version? 
- git reset --hard idVersion(164846)

# Branch

- git branch (list)
- git branch "branchName" (create a new branch)