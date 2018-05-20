# Git workflow

* allways make a pull

* modify files (make beautiful code)

```javascript
console.log("I'm learning git")
```

* verify the differences
```bash git status 
```

* add files to stage 
```bash git add ./ README.md 
```

* commit your changes 
```bash
git commit -m "First commit on develop"
```

* make a push to the repo 
```bash
git push origin master
``` 
* compare 2 branches 
```bash git diff branch1 branch2
```

* make a branch 
```bash git branch branchname
``` 

* delete a branch 
```bash git branch -d branchname
```

* move to a branch 
```bash git checkout branchname
```

* view history 
```bash git log
```

* download a repository from remote to local 
```bash git clone URL
```

Check for alias in git

git config --global alias.lg "log --graph --abbrev-commit --decorate --date=relative --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar
)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"
