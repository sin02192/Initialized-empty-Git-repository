echo "initial" > my_file.txt
git add my_file.txt
git commit -m "Add a new file called my_file.txt"
git checkout -b feature-branch
echo "def login(): pass" > login.py
git add login.py
git commit -m "Add login module in feature-branch"
