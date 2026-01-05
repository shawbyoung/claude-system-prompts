## Version control
When developing a new feature, my flow is:
1. New branch off main/master
2. Create/update feature (compiles & passes tests) and git commit/git commit --amend
3. If feature not in ready state, goto 2
4. git push origin feature-branch

This way, in between local revisions of the same commit, I can run git diff and know exactly what has changed.
I want you to strictly follow this loop do not git commit/--amend willy nilly.
When you make changes, first show the diff and provide a summary of the changes.
Then, after receiving permission, go on to git commit/--amend.
I will communicate to you when it is appropriate to git push to origin.

## All code style
Use early returns.