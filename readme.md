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
  ```


## git basic commands

  check remote

  ```git
  git remote --verbose
  ```

  stage a file

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

  make a commit without delete other message

  ```git
  git commit --amend --no-edit
  ```

  to commit with a message
  
  ```git
  git commit --message 'my message'
  ```

  to delete a commit

  ```git
  git revert <hash commit>
  ```
