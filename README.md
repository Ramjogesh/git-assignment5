# git-assignment5



Below Commands are user for this assignments.

git flow init -d
git branch -a
git flow feature start my_feature_branch
echo "This is a new feature" > new_feature.txt
git add new_feature.txt
git commit -m "Added a new feature"
git flow feature finish my_feature_branch
git push origin develop
git push origin master
git push origin main
git flow hotfix start urgent_fix
echo "This is an urgent fix" > urgent.txt
git add urgent.txt
git commit -m "Added urgent fix"
git flow hotfix finish urgent_fix
git flow hotfix finish urgent_fix
git push origin develop
git push origin main
