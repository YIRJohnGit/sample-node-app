# Sample Node Application for testing

## Making use of GIT
### ...download from GIT Repo and Make Change Push it to Repo
```
git clone git@github.com:YIRJohnGit/sample-node-app.git
git add . # Adding the Git in Local Repo
git commit -am "first update..." # Committing the File
git push --set-upstream git@github.com:YIRJohnGit/sample-node-app.git main
```

### ...or create a new repository on the command line
```
echo "# sample-node-app" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:YIRJohnGit/sample-node-app.git
git push -u origin main
```


### ...or push an existing repository from the command line
```
git add .
git commit -m "first commit"
git remote add origin git@github.com:YIRJohnGit/sample-node-app.git
git branch -M main
git push -u origin main
```