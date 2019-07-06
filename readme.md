# My git commands

## Interact with repository

donwload and clone a repository

```git
git clone <url repository>
```

downloads the new commits from another repository and merges the remote branch into the current branch

```git
git pull origin <branch>
```

Fetching changes from a remote without modifying local branches

```git
git fetch origin <branch>
```

push to your repository

```git
git push origin <branch>
git push --force origin <branch>
```

pushing and setting an upstream branch

```git
git push --set-upstream origin master
git push -u origin master
```

## use branch

add a branch

```git
  git branch <branch name>
```

delete a branch

```git
git branch --delete <branch name>
git branch -d <branch name>
git branch -D <branch name>
```

merge branch

```git
git merge <branch name>
```

change branch and add a branch

```git
git checkout --branch <branch name>
git checkout -b <branch name>
```

## git basic commands

check remote

```git
git remote --verbose
git remote -v
```

save  a file

```git
git add <file>
```

remove a file from git directory

```git
git rm --cached <file>
```

make a commit

```git
git commit
```

modify the most recent commit

```git
git commit --amend
```

to commit with a message

```git
git commit --message 'my message'
```

delete a commit and create a new commit

```git
git revert <hash commit>
```

Temporarily stashing some uncommitted changes

```git
git stash save
```

Reapplying stashed changes

```git
git stash pop
```

try a rebase

## git submodule

create a submodule

```git
  git submodule add <repository url> 
```

  a .gitmodules file

```git
  [submodule "<submodule name>"]
  path = <folder>
  url = <repository url>
```
