git checkout --orphan new_branch
git add . 
git commit -m "new_commit"
git branch -D main
git branch -m main
git push -f origin main
