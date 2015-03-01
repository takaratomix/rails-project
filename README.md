Proiect Licenta
======

This is my project


GitHub commands
=======

After you have modified files and you want to add changes to the Git Repository do the following
* `git add .`
* `git commit -m "A message here to describe the changes"`
* `git push origin master` - to push to the master branch

If you want to reset to a commit use:
* `git reset --hard HEAD` to reset to head (last commit)
* `git reset --hard <commit_id>` to reset to a chosen commit

Git Branching:
If you want to create a new branch run `git branch <name>` and a new branch has been created. Then you switch to that branch using `git checkout <name>` and you push the changes
with `git push origin <name>`. At the end, you can merge the branches from github interface (www.github.com).
If you want to delete a branch you run `git branch -D <name>`