echo "initial" > my_file.txt
git add my_file.txt
git commit -m "Add a new file called my_file.txt"
git checkout master
echo "README update" > README.md
git add README.md
git commit -m "Update README on master"
