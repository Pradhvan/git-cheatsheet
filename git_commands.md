# Git Commands 

#### Get everything ready to commit: 
```BASH
git add --all 
git add .
```

#### Set text editor for git: 

```BASH

git config --global core.editor "subl -n -w"
```
#### Add remote to repo: 
```BASH 
git remote add upstream <original repo link>
git remote add myfork fork_link
```
#### Fetch/Merge changes from upstream 

```BASH
git fetch upstream
git pull upstream master
```

#### Commit changes: 
```BASH 
git commit -m "commit message here"
git commit -m "commint message title here" -m "discription here ..."
git commit 
git commit -am "message"
git commit -a --amend
```

#### Push changes to git 
```BASH
git push origin <branch name> 
git push -f origin <branch-name>
```

#### Branch 
```BASH
git branch 
git checkout branchname 
git branch branchname 
git checkout -b branchname
git merger branchname 
git -d branchname 
git clone -b <branchname> <remote_repo>
```

#### REDO 
```BASH
git reset --soft HEAD^5
git reset --hard [commit]
```