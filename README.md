# Git Cheat Sheet

* Reset
  * [--hard: completely kill a commit(s)](#--hard: completely kill a commit(s)) 
  
* Merge
* Branches


## --hard: completely kill a commit(s)

`git reset --hard @~`

`@` at sign means **HEAD**; `~` tilde references to **parent**; So `git reset --hard @~` will take you one commit back.

