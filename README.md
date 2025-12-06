# Make sure you're on develop branch
git checkout develop

# Add content to README.md
echo "# ALXprodev-advanced_git" > README.md
echo "" >> README.md
echo "This repository demonstrates Git-Flow workflow." >> README.md

# Stage and commit
git add README.md
git commit -m "Add README.md file"

# Push to develop
git push origin develop
