# Skills-GIT
In this repository, I study GIT commands and good practices. Here, I developed a simple calculator program using Python to simulate a git workflow step-by-step.

## Git commands resume

### Step 1: Cloning the Repository
To clone the remote repository to your local machine:
``` bash
git clone https://github.com/example/calculator
``` 

### Step 2: Creating and Switching Branch
To create and switch to a new branch 
```
-git branch feature/example
git checkout feature/example
```

### Step 3: Staging Files
After modifying files, add them to the staging area:
```
-git add index.html
git add style.css

```

### Step 4: Committing Changes
To commit the staged changes with a message:

```
git commit -m "adds shopping cart to layout"

```
### Step 5: Pushing Changes to Remote
To push the feature/example branch to the remote repository:

```
git push origin feature/carrinho-de-compras

```

### Step 6: Merging Branches
To merge the changes from feature/carrinho-de-compras into main (after reviewing and accepting the pull request):

```
git checkout main
git merge feature/carrinho-de-compras

```

### Step 7: Deleting the Branch

Once the branch is merged, you can delete it:



```
git branch -d feature/carrinho-de-compras //deletes local branch

git push origin --delete feature/carrinho-de-compras //deletes remote branch

```

## Other Useful Git Commands

### 1. Check the Status of Your Working Directory
To see which files are staged, unstaged, or untracked:
```
git status
```
### 2. View the Commit History
To view the commit history in a formatted log:

```
git log
```

### 3.Check the Differences Between Staged and Unstaged Files
To see the differences between your working directory and the index:

```
git diff
```

### 4. Create a Tag for a Specific Commit
To create a tag v1.0 for a specific commit:

```
git tag v1.0
```

### 5. Fetch Changes from Remote Without Merging
To fetch changes from the remote without merging them into your current branch:

```
git fetch origin
```




