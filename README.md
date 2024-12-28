# Step 1: Navigate to your project folder
cd /path/to/your/project/folder

# Step 2: Initialize a Git repository
git init

# Step 3: Add a README file
echo "# My Power BI Project" > README.md

# Step 4: Stage all files for commit
git add .

# Step 5: Commit the files
git commit -m "Initial commit - Add Power BI project files"

# Step 6: Link your repository to GitHub
git remote add origin https://github.com/<your-username>/<your-repository>.git

# Step 7: Push the files to GitHub
git branch -M main
git push -u origin main
