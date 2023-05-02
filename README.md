instructions to developers:
git init new-project
cd new-project
git remote add new-project https://github.com/gidra39/new-project
nano README.md
git add README.md
git commit -m "init"
git push --set-upstream new-project master
git branch development
git checkout development
nano README.md
git add README.md
git commit -m "random"
git push --set-upstream new-project development
git checkout master
git merge development
git status
git push
