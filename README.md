
# Top Useful Git commands: Everyone must know these commands.

***Download Now*** 

[![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)

## Initialize

```bash
git config --global user.name [your name]

git config --global user.email [youremail@example.com]
```

```bash
git init -[to initalize empty git repoistory]
```
```bash
touch.gitignore -[to create a new file using "touch" cmd]
```
## Track files
```bash
git add [file-name] -[to add untracked file from unstaging area]

git add -A  -[to add all untracked files]
```
## Unstaging files
```bash
git rm --cached [filename] -[remove the file from staging area]

git reset [file name] -[to convert from staging to unstaging area] 
```
## Commit and Status
``` bash
git commit -m "[commit name]" -[to save checkpoint]

git status -[just to see the status, what happens on files]
```

``` bash
git log -[shows changes]

git log -p -1[no. of commits] -[shows all changes with commit]

```
## Compare the last commit

``` bash
git checkout [filename] -[ match the file from last commit]

git checkout -f -[match the all files from last commit]

```
## from Staging area and Working directory

``` bash
git diff -[it compare working directory from staging area]

git diff --staged -[ it compare staging area from last commit]

git commit -a -m "[commit name]" -[skip from staging area(modified)]
```
## Remove a file
``` bash
git rm [filename] -[remove the file from staging and hard drive]

git rm --cached [filename] -[remove the file from staging area]
```
## Working with branch
``` bash
git branch [branch name] -[create a new branch]
git checkout [branch name] -[switch to branch]

git branch - M [new branch name] -[rename of current branch]

git branch -[shows a branch]

git checkout -b [branch name] -[it will create and switch to new branch]

git merge [branch name] -[merge into the main branch]

```
## Working with remote repoistory

``` bash
git remote add origin [URL.git] -[to add url/remote of the repo]

git remote -v -[to check whether remote is added or not ]

git remote set-url origin [URL.git] -[to set/change url of remote ]

git push origin [branch name] -[to push from local to remote]

git push -u origin [branch name] 
git push -[it will push to same remote without using(git push -u origin master)]

git pull -[to fetch from remote to local]
```

## Clone a repo

``` bash
git clone [UR.git] [folder name] -[cloning into folder from remote]
```


## 🔗 *Connect with me*
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dashminder-singh)

[![Instagram](https://img.shields.io/badge/<handle>-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/__dashmindersingh__/)


