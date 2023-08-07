# GIT 
`Git` is a software that allows you to keep track of changes made to a project over time. Git works by recording the changes you make to a project, storing those changes, then allowing you to reference them as needed. Git is a Distributed Version Control System. 

## Git Workflow
1- A `Working Directory`: where you’ll be doing all the work: creating, editing, deleting and organizing files. 
2- A `Staging Area`: where you’ll list changes you make to the working directory.  
3- A `Repository`: where Git permanently stores those changes as different versions of the project.  

## command:
- `init` : The command sets up all the tools Git needs to begin tracking changes made to the project.
- `git status`
- git add .gitignore
- `git add -A`
- git reset (return it to the working directory/remove everything from the stageing area)
- Commit: git commit -m "initial commit"
- clone: git clone <url> where to clone
- to see hte info about colning use `git branch -a` or `git remote -v`
- pushing changes: `git diff` --> `pull , push`.
- create a branch: `git branch <name> --> git git checkout <name>` using branch to desire features.
  --> then push the branch to the remote using `git push -u origin <name> , git branch -a`.
- merge a branch:
```git
 $git checkout master
 $git pull origin master
 $git branch --merged
 $git merge <name>
 $git push origin master
 
```
- deleting a branch:
```git
 $git branch --merged
 $git branch -d <name>




 $git branch -a
 $git push origin --delete <name>


```
` HEAD answers the question, “Where am I right now?”`
 
