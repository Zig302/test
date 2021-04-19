# Working with git:

## On the first time:
1) git clone https://github.com/omertub/beginners-git-course
2) cd beginners-git-course

## Creating a new feature branch:
1) git branch <branch-name>
2) git checkout <branch-name>
### or
4) git checkout -b <branch-name>

## Developing a feature:
1) git checkout <branch-name>
2) git status (red)
3) git add <filename>
4) git status (green)
5) git commit -m "commit message"
6) At the end of the day: git push origin <branch-name>
### or
6) git push (when you inside the branch)

## When the feature is completed:
1) add -> commit -> push
2) Create PR on github
3) Confirm PR (or wait for your friends CR)

## Pull develop updates to your current branch:
1) git checkout <branch-name>
2) git pull origin develop
In case there is conflicts - solve them in VS code

## Remarks
1) For bugfixes or hotfixes open a branch: bugfix/XX, hotfix/XX
2) Don't work on the master branch!

## Extra:
1) git log - View all the previous commits of the current branch.
2) git diff - View all the changes compare to the last commit.
