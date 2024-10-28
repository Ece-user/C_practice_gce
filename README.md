# C_practice_gce
This repo is used to manage work from C training and proctice git functions

Git cheat sheat :

# Initialize a repository
git init
 
# Clone a repository
git clone <repository-url>
 
# Check repository status
git status
 
# Add changes to staging
git add <file>                # Add a specific file
git add .                     # Add all changes
 
# Commit changes
git commit -m "Commit message"
 
# View commit history
git log
 
# Branching
git branch <branch-name>      # Create a new branch
git checkout <branch-name>    # Switch to a branch
git checkout -b <branch-name> # Create and switch to a new branch
git branch                     # List branches
git branch -d <branch-name>    # Delete a branch (safe)
git branch -D <branch-name>    # Force delete a branch
 
# Merging
git merge <branch-name>       # Merge a branch into current branch
 
# Remote repositories
git remote add <name> <repository-url> # Add a remote
git remote -v                  # View remote repositories
git push <remote-name> <branch-name> # Push changes
git pull <remote-name> <branch-name> # Pull changes
 
# Undoing changes
git reset <file>              # Unstage changes
git reset --soft HEAD~1       # Revert last commit (keep changes)
git checkout -- <file>        # Discard changes
 
# Tags
git tag <tag-name>            # Create a tag
git push <remote-name> --tags  # Push tags to remote
 
# Configuration
git config --global user.name "Your Name"     # Set user name
git config --global user.email "your.email@example.com" # Set user email
 
# Help
git help <command>            # Get help for a command