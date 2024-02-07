…or create a new repository on the command line
echo "# MYRepository" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/drouthu/MYRepository.git
git push -u origin master