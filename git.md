# Git & GitHub Cheatsheet

## 1. Configuration
- **Set user name:**  
  ```bash
  git config --global user.name "Your Name"
  ```
- **Set email address:**  
  ```bash
  git config --global user.email "your.email@example.com"
  ```

## 2. Repository Initialization
- **Initialize a new repository:**  
  ```bash
  git init
  ```

- **Clone an existing repository:**  
  ```bash
  git clone <repository_url>
  ```

## 3. Status and Logs
- **Check repository status:**  
  ```bash
  git status
  ```

- **View commit logs:**  
  ```bash
  git log
  ```

## 4. Adding and Committing Changes
- **Add specific file(s):**  
  ```bash
  git add <file(s)>
  ```

- **Add all changes:**  
  ```bash
  git add .
  ```

- **Commit changes with a message:**  
  ```bash
  git commit -m "Your commit message"
  ```

- **Commit changes with all staged files and a message:**  
  ```bash
  git commit -a -m "Your commit message"
  ```

## 5. Branching and Merging
- **List all branches:**  
  ```bash
  git branch
  ```

- **Create a new branch:**  
  ```bash
  git checkout -b <new_branch_name>
  ```

- **Switch to a different branch:**  
  ```bash
  git checkout <branch_name>
  ```

- **Merge a branch into the current branch:**  
  ```bash
  git merge <branch_name>
  ```

## 6. Pushing and Pulling
- **Push changes to a remote repository:**  
  ```bash
  git push <remote_name> <branch_name>
  ```

- **Pull changes from a remote repository:**  
  ```bash
  git pull <remote_name> <branch_name>
  ```

- **Fetch changes without merging:**  
  ```bash
  git fetch <remote_name>
  ```

## 7. Remote Repositories
- **Add a remote repository:**  
  ```bash
  git remote add <remote_name> <repository_url>
  ```

- **List all remote repositories:**  
  ```bash
  git remote -v
  ```

- **Remove a remote repository:**  
  ```bash
  git remote rm <remote_name>
  ```

## 8. Stashing and Resetting
- **Stash changes:**  
  ```bash
  git stash
  ```

- **Apply stashed changes:**  
  ```bash
  git stash apply
  ```

- **Reset to a previous commit (soft reset):**  
  ```bash
  git reset --soft <commit_id>
  ```

- **Reset to a previous commit (hard reset, destructive):**  
  ```bash
  git reset --hard <commit_id>
  ```

## 9. GitHub Collaboration
- **Create a pull request:**  
  1. Go to your repository on GitHub.
  2. Click on the "Pull requests" tab.
  3. Click on "New pull request."
  4. Select the branches to compare, then click "Create pull request."

- **Review and merge a pull request:**  
  1. Click on the pull request to review.
  2. After review, click "Merge pull request" if approved.

## 10. Miscellaneous
- **Display Git configuration:**  
  ```bash
  git config --list
  ```

- **Display help for a command:**  
  ```bash
  git help <command>
  ```

