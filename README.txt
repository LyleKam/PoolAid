This project is designed to help new pool players develop their skills by offering a tool to help them aim!


If you're making a commit, please initiate a branch first, back it up, commit, then push to master.
1. Clone master branch git clone: https://github.com/LyleKam/PoolAid.git
2. Create a new branch for development git checkout -b new_branch
3. Now you can make your changes to PoolAid
4. Add modified/created files to branch git add files
5. Commit files git commit ***
6. Backup your development branch git branch new_branch_backup
7. Move to the master branch git checkout master
8. Update the master branch git pull
9. Optional file selection: git checkout files_you_want_to_remain_the_same
10. Go back to your development branch git checkout new_branch
11. Rebase the development branch onto the master branch git rebase master
12. Push your changes to GitHub: git push --set-upstream origin new_branch

Note:
gitignore is a file used to list the repository files you want git to ignore during commits. We ignore the following:
.gitignore
*.csv
*.png
*.json


COMMIT MESSAGE ETIQUETTE:
If you're making changes, note the convention:
feat: (new feature for the user, not a new feature for build script)
fix: (bug fix for the user, not a fix to a build script)
docs: (changes to the documentation)
style: (formatting, missing semi colons, etc; no production code change)
refactor: (refactoring production code, eg. renaming a variable)
test: (adding missing tests, refactoring tests; no production code change)
chore: (updating grunt tasks etc; no production code change)

*Add the type of change followed by a brief message of what you changed. (If your change doesn't fit here, just write the message)
** For more info, here is the style guide for commits: https://udacity.github.io/git-styleguide/