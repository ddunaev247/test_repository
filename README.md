echo "# test_repository" >> README.md
git init 
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:ddunaev247/test_repository.git
git push -u origin master

