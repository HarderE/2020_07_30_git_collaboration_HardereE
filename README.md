# Git Collaboration class notes

## Cloning
- `git clone <url>`: todownload repository from web to local computer
    - make sure to not nest this command into another repository
    - just like `git init`, only do this onece per repo

## Branches
- `git branch <branch_name>`: create a new branch
- `git switch <branch_name>`: move to a branch
  - `git checkout <branch_name>`: the pre-august version for git switch
- `git switch -c <branch_name>`: create and move to a branch in one step
  - same as `git checkout -b <branch_name>`

- `git log --oneline --graph --decorate`: shows you your git history tree
  - you can look up how to set this as an git alias

## Pull request (Online merge)

- `git push origin <branch_name>´: push the branch into remote (GitHub)
-  In REMOTE: 
   - Issue a pull request
   - Merge the pull request 
   - delete the branch manually under the branches view

To sync your local computer:
- In your computer:
   - `git checkout master`: go back to thr master
   - `git pull origin master`: Pull down merged code
   - `git branch -d <branch_name>`: remove the branch from your loval computer
   - `git fetch --prune`: clean up git history and remove references from remote that no longer exists

