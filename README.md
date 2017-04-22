# One page for esprit libre club

## Development Workflow

1. clone project
2. get assigned a ticket
3. create new branch starting with the ticket number as the name `git checkout -b 31-some-branch-name`
4. make some commits and changes
5. push branch and commits to remote
6. create pull request for your branch
7. assign another developer or a project manager to review your PR
8. if you get assigned a PR for review you are also responsible for code quality and testing.
9. if you sport any bugs ask the developers to fix them first, then you can merge the PR when it is ready.
10. check that the PR merge does not break anything on master.

## Git steps

1. git clone some-ssh-url-or-https
2. cd project-folder
3. git pull
4. git checkout -b 31-some-branch-name
5. make changes
6. git status
7. git diff
8. git add .
9. git status
10. git commit -m 'message'
11. git status
12. git log
13. git push
14. go back to step 5 to add more commits, other wise proceed to step 15
15. go on github, create a PR and assign a reviewer.

## Extra git commands
* see your branch: `git branch`
* see remote branches: `git branch -r`
* reset modifications in the current local branch: `git checkout .` or `git checkout file-name`
* switch to another branch: `git checkout branch-name`, could be `git checkout master` or `git checkout 31-some-branch-name`
* to rebase master into your current feature branch (31-some-branch-name): `git rebase master`
* to merge master into your current feature branch (31-some-branch-name): `git merge master`
* to resolve a conflict: `git mergetool -t kdiff3` or `git mergetool -t meld`

