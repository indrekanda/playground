The commands to set up git and push your local playground repository:
```bash
# Initialize git repository (if not already done)
git init

# Add the remote repository
git remote add origin https://github.com/indrekanda/playground.git

# Add all files to staging
git add .

# Create initial commit
git commit -m "Initial commit: Add README and .gitignore"

# Push to remote repository (first time)
git push -u origin main
```



If you get an error about the branch name, you might need to rename your branch to main:
Note: Since the remote repository already has a LICENSE file, you might want to pull it first to avoid conflicts:
The --allow-unrelated-histories flag is needed because your local repository and the remote repository have different commit histories (the remote has the LICENSE file, your local has the README and .gitignore).
Run these commands in your /home/indre/projects/playground directory, and your playground repository will be properly set up and pushed to GitHub!