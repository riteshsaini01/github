# Github commands

All github commands

## First time adding in new repo

*Step 1. common commands for all branches*

```
$ git init 
```
```
$ git add README.md
```
```
$ git commit -m "first commit"
```
```
$ git branch -M main
```
```
$ git remote add origin https://github.com/riteshsaini01/github.git
```
```
$ git push -u origin main
```

*Step 2. Second time adding in same repo*

```
git add .
```
```
git commit -m "Name of Commit"
```
```
git push
```

*Step 3. Creating and managing branch*

```
git branch
```
```
git branch -c nameofbranch 
```
```
git checkout branchname--->to shift into a particular branch
```
```
git pull--->used to fetch and download content from a remote repository and immediately update the local repository to match that content
```

*Step 4. Pushing into new sub banch*

```
git push origin head
```