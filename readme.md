# <font color=purple> Git & Github commands and Instructions!</font>

* `git init` - Used to initialize a git repository 
* `git status` - Checking status of the repository
  * `-s`- shows the shorthand status
* `git add` - stage the tracked files
  * `-A` - this flag selects all.
* `git commit -m "Commit Message"` - Takes snapshot of your code
* `git rm` - deletes files from remote and local repository
  * `-cached` - only removes files form staged area
* `git checkout` - restores code to it's last committed state.
  * `-f` - selects all the files and folders
* `git log` - shows all the commits made previously 
  * `-p -[number of repos]`- number of repos you want to see
* `git diff`- compares repo and local code
  * `-stage`-compares only staged once
* `git branch <name of the branch>`- creates a new timeline
  * `git checkout <name of the branch>` - switches to the branch
  * `git checkout -b <name of the branch>`- does both at the same time
  * `git merge <source-branch>`- marge
  