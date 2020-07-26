# Git Cheat Sheet

* Reset
  * `git reset --hard`: I did not commit anything but changed a lot of files. I'd like to start over again
  * `git reset --hard @~`:  I made a bad very bad commit. I'd like to get rid of it
  
* Merge
* Branches

## git reset --hard

Assume you changed 50 files and you have not commited anything yet. If you run `git status` you will see **those 50 files have been modified**. You would like to start over again have it clean repository so type this:

`git reset --hard`

The command above will clear all modified files. Notice that you specify nothing after --hard flag that means clear all to the current commit you are now. 


## git reset --hard @~

Assume you have done just one bad commit. I do not like it at all and you'd like to delete it forever as if it never even existed. Do this:

`git reset --hard @~`

`@` at sign means **HEAD**; `~` tilde references to **parent**; So `git reset --hard @~` will take you one commit back. Now technically (you still can restore it) Git knows nothing about your bad commit.

