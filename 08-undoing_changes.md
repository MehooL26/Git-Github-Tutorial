## Undoing Changes
- sometimes we unintentiolly add or commit changes, to undo them :

### Case 1 : staged changes 
  *git reset <-file name->* <br>
  *git reset* <br>

### Case 2 : commited changes (for one commit)
  *git reset HEAD~1* <br>

### Case 3 : commited changes (for many commits)
  *git reset <-commit hash->* <br>
  *git reset --hard <-commit hash->* <br>
