# Git Exercise 1

# Gym Git Exercise Solutions

## Exercise 1

```bash
mkdir git-exercise-1
cd git-exercise-1
git init
echo "# Git Exercise 1" > README.md
echo "<h1>Git Exercise 1</h1>" > index.html
git add .
git commit -m "Initial commit with README and index.html"
git branch -m master main
git remote add origin https://github.com/<your-username>/git-exercise-1.git
git push -u origin main
git checkout -b dev
git checkout -b test
git checkout dev
git branch -d test
git push origin main
git push origin dev
```
