This is `playground.md` file in main branch.
#git workshop
stelios Chatzis

20/11/25

This is my first notes on git:

SAVE SECTION:

*Add smth and save on git history (AKA: stage a file)-> git add

*Save a version (almost like add)-> git commit -m "message"

*Send to github -> git push origin main
    
    STASH:

    *Save staged && unstaged changes LOCALY (NOT part of git history)-> git stash (push <file>)

    *See your stash list-> git stash list

UNDO CHANGES AND RESTORE SECTION:

*Delete smth -> git restore 
NOTE: if i have saved my changes on git (git add) it doesnt work => 1) Git restore --staged <file> 2) git restore <file>

*Undo last commit -> git reset HEAD~1
    STASH:
    *Delete a specific stash (e.g., stash@{0}) -> git stash drop <stash>    
