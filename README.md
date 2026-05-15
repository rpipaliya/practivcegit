# Git Beginner Step-by-Step Commands

# 1. Initialize a new Git repository
git init
# Purpose:
# Creates a new local Git repository inside the folder.

# 2. Check repository status
git status
# Purpose:
# Shows tracked, untracked, staged, and modified files.

# 3. Add a single file to staging area
git add README.md
# Purpose:
# Prepares README.md for commit.

# 4. Add another file
git add git-cheat-sheet-education.pdf
# Purpose:
# Adds PDF file to staging area.

# 5. Remove file from staging area only
git rm --cached git-cheat-sheet-education.pdf
# Purpose:
# Unstages the file but keeps it in the folder.

# 6. Create first commit
git commit -m "This is my First Commit"
# Purpose:
# Saves staged changes permanently in Git history.

# 7. Rename branch from master to main
git branch -M main
# Purpose:
# Changes default branch name to main.

# 8. Check current branch
git branch
# Purpose:
# Displays available branches and current branch.

# 9. Add remote GitHub repository
git remote add origin https://github.com/rpipaliya/practivcegit.git
# Purpose:
# Connects local repository with GitHub repository.

# 10. Verify remote repository
git remote -v
# Purpose:
# Shows fetch and push URLs of remote repository.

# 11. Push code to GitHub
git push -u origin main
# Purpose:
# Uploads local commits to GitHub and sets upstream branch.

# 12. Configure Git username globally
git config --global user.name "Rushil Pipaliya"
# Purpose:
# Sets author name for all Git commits.

# 13. Configure Git email globally
git config --global user.email "rpipaliya@stud.hs-heilbronn.de"
# Purpose:
# Sets author email for all Git commits.

# 14. Add modified file again
git add README.md
# Purpose:
# Stages updated changes.

# 15. Create second commit
git commit -m "This is my Second Commit"
# Purpose:
# Saves new changes in commit history.

# 16. Push latest changes to GitHub
git push origin main
# Purpose:
# Uploads latest commits to GitHub.

# Useful Extra Commands

# Check complete commit history
git log
# Purpose:
# Shows all commits with commit IDs.

# Show short commit history
git log --oneline
# Purpose:
# Displays compact commit history.

# Clone existing repository
git clone <repository-link>
# Purpose:
# Downloads repository from GitHub to local machine.

# Pull latest changes from GitHub
git pull origin main
# Purpose:
# Downloads and updates latest changes from remote repository.

# Show differences in files
git diff
# Purpose:
# Displays unstaged file changes.

# Unstage a file
git restore --staged <file-name>
# Purpose:
# Removes file from staging area.

# Delete a tracked file
git rm <file-name>
# Purpose:
# Removes file from Git and local folder.