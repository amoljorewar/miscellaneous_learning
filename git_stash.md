#Git stash is a built-in command in Git that temporarily stores changes in a workspace so that developers can work on other things and then return to them later: 
##Git stash
###What it does - Saves changes in a stash stack and resets the workspace to its previous commit state
###When to use it - When you need to switch context and work on something else, but you're not ready to commit
###How it works - Stores changes locally, hidden from other developers who share the same Git repository
###Commands - git stash list to list stashes, git stash show to inspect stashes, git stash apply to restore stashes


#Here are some things to know about Git stash:
•	Stashed files include untracked files, newly added files, and modified files. 
•	The latest stash is stored in refs/stash and older stashes are found in the reflog of this reference. 
•	The default list name for a stash is "WIP on branchname". 
•	You can give a more descriptive message on the command line when you create a stash. 
•	Stashed changes can be reapplied at any time, even on a different branch. 
•	Pushing changes doesn't replicate the stashed code to remote Git repositories.
