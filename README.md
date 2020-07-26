# Git Cheat Sheet

* Reset
  * --hard: completely kill a commit(s)
  
* Merge
* Branches


## --hard: completely kill a commit(s)

Assume you have done just one bad commit. I do not like it at all and you'd like to delete it forever as if it never even existed. Do this:

`git reset --hard @~`

`@` at sign means **HEAD**; `~` tilde references to **parent**; So `git reset --hard @~` will take you one commit back. Now technically (you still can restore it) Git knows nothing about your bad commit.

