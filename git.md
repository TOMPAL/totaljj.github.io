# With Git for Windows 2.7.3+ (March 2016):
```
git config --global credential.helper manager
```


# linux
```
git config --global credential.helper "cache --timeout=3600"
```


# command
```bash
git init
git clone
git add * -A
git commit -m 'message'
git push -u origin master

git branch
git branch new-branch {master}
git checkout -b new-branch {master}
 or 
git checkout new-branch


git stash save {name}
git reset --hard origin/master
git stash list
git stash apply stash@{0}

git pull
```
