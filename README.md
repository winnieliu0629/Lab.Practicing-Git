--This is a repo for learning git

## Setting up the connection to Github
### step 1: create a new repository

```
mkdir ./example-repository
cd example-repository
git init
```
### step 2: add a new file

```
touch README.md
echo "This is a repo for learning git" >> README.md
```

### step 3: stage/commit the changes

```
git add README.md
git commit -m "adds README.md"
```

### step 4: create a new github repo *-"push an existing repository from the command line"*

```
git remote add origin YOUR-GITHUB-LINK-HERE
git branch -M main
git push -u origin main
```