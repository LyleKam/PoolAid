This project is designed to help new pool players develop their skills by offering a tool to help them aim!


If you're making a commit, please initiate a branch first, back it up, commit, then push to master.
- $ git branch checkout -b <branch>
- Make changes
- Commit changes
- $ git branch checkout <branch_backup>
- git push --set-upstream origin master

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