## GitHub Actions

### How to use collaboration actions in github


### 1.create an empty folder to your c:\

- ex. c:/new-project

- navigate to github page inside the collab project and press fork

"a clone of collab repository was created in your repositories"

- Go to your repositories and find the cloned repo

## How clone repository locally:

Install github cli :

```code
winget install --id GitHub.cli
```

Next navigate to your empty folder (ex.c:/new-project) to clone github repository with cli run:

```code
gh repo clone <github-name/project-name>
```

then run:
```code
git status 
```
 
"On branch main"

---
### How to create a new branch

- Create and switch to the new branch named "test-branch":

```code
git checkout -b test-branch
```

To add the main code to your branch run:

```code
git add .
git commit -m "new branch"
```

And: 
```code 
git status
```
"On branch test-branch
nothing to commit, working tree clean"

### How to push code to collab repository:

```code 
git push -u origin test-branch
```

- Create a pull request for 'test-branch' on GitHub collab repository by pressing "Create pull request"







