# Remove Commits
   ```bash
git checkout --orphan new_branch
git add .
git commit -m "update"
git branch -D main
git branch -m main`
git push -f origin main

