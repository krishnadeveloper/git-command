# git command
### Some useful commands which are used most of time
1. To create a clone from Git http(s) url

`git clone https://github.com/krishnadeveloper/git-command.git`

2. Push or commit a perticular file in master origin

```
git add filename (text.txt)
git commit -m "You comment"
git pish origin master
```
3. Push or commit all changes from your system git directory to master origin

```
git add -A
git commit -m "You comment"
git push origin master
```

4. Pull or fetch all changes from master origin to your system git directory

```
git fetch
git merge
git pull
```
5. If you have created another branch and want to use that branch 
`````
git clone your_git_repository_url
git checkout -b your_branch_name
git add - A
git commit -m “Your comment”
git push origin your_branch_name
`````
