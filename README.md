# git Learn
## Git Init
> To intiate git you can use
```git
git init
```
## To see The version of git 
> The command for it is:
```git
git --version
```
## To make a commit
> It is useful to make a commit like doing a snap
```
git add file or directory
git commit -m "your comment here"
```
## To see the evolution of the file
> To know the evolution of your file inside the git you need to use the command
```git
git status
```
## To compare your file with the last version
> To compare your actual file with the previous version

>The command to use is:
```git
git diff 
git diff your_file
```
## To see the history
> To find all the history we have the command
```git
git log
```
All the bunch of number is called SHA of the commit. Here is the link to know the meaning of [SHA](https://en.wikipedia.org/wiki/SHA-1)
## Go back to the last history
> There are two ways of going back in git.
1. Number One
```git 
git checkout your_cha_number
```
To return back to the master branch

You can use:
```git
git checkout master
```
2. Number Two

Totally return to the back\
You have the command:
```git
git reset --hard sha_name
```
OR 

```git
git reset --hard
```
## Remote in github
> This is the way to make a remote in github:
```git
 git remote add origin ton_url
```
## Play with the remote
1. Push
```git
git push
git push origin master
git pull remote_name branch_name
```
2. Pull
```git
git pull
git pull origin master
git pull remote_nam branch_name
```