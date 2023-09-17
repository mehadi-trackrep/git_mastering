#Section - 1:(Branches)
```
    * git branch
    * git branch -r
    * git branch -a
```
#Section - 2:(Logging, Reflog)
```
    * git log
    * git log -5
    * git log <branch>
    * git log --name-only
    * git log --name-status
    * git log --since=1.day.ago
    * git log --follow <file_name>
    * git log --oneline -5
    * git log --oneline --graph --decorate --all
    * git log --oneline --graph --decorate --all --author="Sandeep" --before="2019-01-01" --after="2018-01-01" --grep="Initial" --grep="Added"
    * git reflog
```
#Section - 3:(Stashing)
```
    * git stash
    * git stash list
    * git stash apply
    * git stash apply stash@{1}
    * git stash drop
    * git stash pop
    * git stash clear
```
#Section - 4:(Cherry-pick, Revert)
```
    * git cherry-pick <c1>
    * git cherry-pick <c1>..<cn>
    * git revert <c1>
    * git revert <c1>..<cn>
    * git revert <c1>^..<cn> --no-commit
```
#Section - 5:(Ammend, Merging)
```
    * git commit --amend
    * git commit --amend --no-edit
    * git merge <branch_name>
    * git merge --abort
    * git merge --continue
    * git merge --no-ff <branch_name>
```
#Section - 6:(Resetting)
```
    * git reset --soft <commit_hash>
    * git reset --mixed <commit_hash>
    * git reset --hard <commit_hash>
```
