
Git Collaboration class notes

# Cloning
- `git clone <url>`: todownload repository from web to local computer
    - make sure to not nest this command into another repository
    - just like `git init`, only do this onece per repo

# Branches
- `git branch <branch_name>`: create a new branch
- `git switch <branch_name>`: move to a branch
  - `git checkout <branch_name>`: the pre-august version for git switch

# Merging
- `git push origin <branch_name>´: push the branch into remote (GitHub)
-  In REMOTE: 
   - Issue a pull request
   - Merge the pull request 
   - delete the branch manually under the branches view
- In your computer:
   - `git checkout master`: go back to thr master
   - `git pull origin master`: Pull down merged code
   - `git branch -d <branch_name>´: delete the branch
   - `git fetch --prune`: clean up the branch

