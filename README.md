# THIS IS A README FILE FOR USING GIT PROPERLY #
how to use git:
## initialize project ##
1. create folder including all relevant files
2.  
```bash
git init
git add .
git commit -m "first init"
```
3. create project in gitHub
4. copy commands from gitHub to bash and execute
5.  
```bash
git push
```
6. the other team member copies the link of the gitHub repository, and clones to his local folder.

## workflow ##
1. pull the last changes:
```bash
git pull
```
2. create new branch for the feature:
```bash
git branch <branch>
get checkout <branch>
```
3. edit code
4. save changes:
```bash
git add .
git commit -m "updated version"
```
5. move to main branch:
```bash
git checkout main
```
6. merge changes:
```bash
git merge <branch>
```
7. push changes:
```bash
git push
```
8. delete local branch:
```bash
git branch -d <branch>
```