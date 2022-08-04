# Git commands 
*This repo contains all the common and necessary git commands*
## Git setup command
> Configuration of Git to Github
```
git config --global user.email "example@email.com"
git config --global user.name "Janet Doe"
```
## Initializing a repo
```
git init
```
## Checking Status
```
git status
```
> The git status command is used to check if a directory is git enabled and also to check the status of our file whether staged, committed or pushed 

> git init
it is used to initialize a directory in git repo

## Staging Changes 
```
git add file name
git add .
```
> The `git add filename ` is used to stage a single file while  `git add` is used to add a file

## Committing Changes 
```
git commit - m "commit message"
git commit -a -m "commit message"

```
> The first command in the block above is used to commit a file that has been recently staged, while the second command is used to add and commit a file that git is already tracking.

## Setting up a remote connection
- Checking if a connection already exists
```
git remote -v
```
- Adding a remote connection
```
git remote add "connection name" "connection URL"
eg. git remote add origin https://github.com/username
```
- Remove a remote connection
```
git remote "connection name" 
eg. git remote remove origin 
```