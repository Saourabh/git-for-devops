# Git Commands Cheat Sheet

## Initialization and Setup
- **`git init`**  
  Initializes a new Git repository in the current directory.

- **`git config --global user.name "Your Name"`**  
  Sets your username for all repositories on your machine.

- **`git config --global user.email "your-email@example.com"`**  
  Sets your email address for all repositories on your machine.

## Checking Repository Status
- **`git status`**  
  Displays the state of the working directory and the staging area.

## Staging and Committing Changes
- **`git add <file>`**  
  Stages a specific file for commit.

- **`git add .`**  
  Stages all changes (new, modified, or deleted files).

- **`git commit -m "Commit message"`**  
  Records the staged changes with a descriptive message.

## Branching and Merging
- **`git branch`**  
  Lists all branches in the repository.

- **`git branch <branch-name>`**  
  Creates a new branch with the given name.

- **`git checkout <branch-name>`**  
  Switches to the specified branch.

- **`git switch <branch-name>`**  
  Switches to the specified branch (alternative to `checkout`).

- **`git checkout -b <branch-name>`**  
  Creates a new branch and switches to it.

- **`git merge <branch-name>`**  
  Merges the specified branch into the current branch.

## Viewing Logs and History
- **`git log`**  
  Displays the commit history.

- **`git log --oneline`**  
  Shows a summarized one-line-per-commit log.

## Handling Unstaged Changes
- **`git restore <file>`**  
  Restores the specified file to the last committed state.

- **`git rm --cached <file>`**  
  Removes the file from the staging area without deleting it from the working directory.

## Undoing Commits
- **`git reset --soft <commit>`**  
  Moves the HEAD to a specific commit but keeps changes staged.

- **`git reset --hard <commit>`**  
  Moves the HEAD to a specific commit and discards all changes.

## Remote Repositories
- **`git remote add origin <repository-url>`**  
  Adds a remote repository as `origin`.

- **`git push origin <branch-name>`**  
  Pushes the branch to the remote repository.

- **`git pull origin <branch-name>`**  
  Fetches and merges changes from the remote branch.

## Helpful Tips
- **`git log --graph --decorate --oneline`**  
  Displays the commit history as a graph with branch decorations.

- **`git diff`**  
  Shows the difference between the working directory and the staging area.

- **`git stash`**  
  Temporarily saves uncommitted changes for later use.

- **`git stash pop`**  
  Restores the saved changes from the stash.
