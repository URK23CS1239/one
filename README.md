git init
echo "Project" > README.md 
git add . git commit -m "first" 
git checkout -b hello 
echo "hello" > hello.txt 
git add . 
git commit -m "hello added"
git remote add origin https://github.com/<username>/repo.git
git push -u origin hello 
git checkout main
git merge hello
git push

git remote set-url origin https://github.com/URK23CS1239/two.git
git push -u origin main

git init
echo "Project" > README.md
git add .
git commit -m "first"

git remote add origin https://github.com/<username>/repo.git
git push -u origin main

git checkout -b hello
echo "hello" > hello.txt
git add .
git commit -m "hello"

git push -u origin hello

git checkout main
git merge hello
git push
