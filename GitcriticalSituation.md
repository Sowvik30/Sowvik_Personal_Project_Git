## if there is situation where files were commited but you were unable to push it due some files
and the message is 
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

The to handle this command will be: 

## Undo Commits but Keep Changes
git reset --soft HEAD~N

## Undo Commits and Unstage Changes
git reset HEAD~N

## Undo Commits and Discard Changes
git reset --hard HEAD~N

## Revert Commits (Safe for Shared Repos)
git revert <commit-id>

## Interactive Rebase (Ideal for cleaning up messy commit history.)
git rebase -i HEAD~N

## Want to Inspect Before Undoing?
git log --oneline
