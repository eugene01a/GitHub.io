# GitHub.io

#Create Github repo

To avoid errors, do not initialize the new repository with README, license, or gitignore files. Add these later

origin = where local repo will be pushed to

Create new repo on github first, then do following:

```
cd <local project>
git init
git add .
git commit -m "First commit"
git remote add origin https://github.com/<user>/<repo_name>.git 
git remote -v #Verifies the new remote URL
git push -u origin master
```
