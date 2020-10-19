## Rebase sandsox

Try to rebase branch and squash commits.

### Quick start

#### …or create a new repository on the command line
```
echo "# rebase-sandbox" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/artkostya/rebase-sandbox.git
git push -u origin main
```
                
#### …or push an existing repository from the command line
```
git remote add origin https://github.com/artkostya/rebase-sandbox.git
git branch -M main
git push -u origin main
```

### Switch to branch
```
git checkout <branch>

### Edit commit

git commit --amend -m "Change commit"


