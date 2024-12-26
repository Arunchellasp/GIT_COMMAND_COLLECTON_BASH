GIT COMMANDS SEQUENTIAL GUIDE

# 1. Initial Repository Setup

# Initialize a new Git repository
git init

# Configure user information (one-time setup)
git config --global user.name "Your Name"


git config --global user.email "your.email@example.com"

# 2. Adding Files and Directories

# Add specific file
git add filename.txt


# Add specific directory
git add directory_name/


# Add all files and directories
git add .


# Check status of working directory
git status

# 3. Remote Repository Setup


# Add remote repository (origin)
git remote add origin https://github.com/username/repository.git


# Verify remote
git remote -v

#4. Branch Operations

# Create new branch
git branch branch_name

# Switch to branch
git checkout branch_name

# Create and switch to new branch (shorthand)
git checkout -b branch_name

# List all branches
git branch

# List all remote branches
git branch -r

# List all local and remote branches
git branch -a


# 5. Permissions and Access Control


# Make files executable
git update-index --chmod=+x filename



# Configure SSH key (for secure authentication)
ssh-keygen -t ed25519 -C "your.email@example.com"

# 6. Commit Operations

# Commit changes with message
git commit -m "Your commit message"

# Commit all tracked files
git commit -am "Your commit message"

# List commits
git log

# List commits in compact format
git log --oneline


# 7. Push and Pull Operations

# Push to remote repository
git push origin branch_name


# Push and set upstream branch
git push -u origin branch_name


# Pull from remote repository
git pull origin branch_name



# Fetch remote changes without merging
git fetch origin


# 8. Common Additional Commands


# Check differences
git diff


# Discard changes in working directory
git checkout -- filename


# Remove files from staging area
git reset filename


# Merge branch into current branch
git merge branch_name
