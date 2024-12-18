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

```bash
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add .\home.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git adPS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git adPS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add .\home.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "added home.html"
[dev 928e93b] added home.html
No local changes to save
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add .\about.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "added about.html"
[dev 3e1cfd7] added about.html
 1 file changed, 11 insertions(+)
 create mode 100644 about.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash
No local changes to save
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>



                                                                   git add .\team.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "add team.html"
[dev d19df2b] add team.html
 1 file changed, 11 insertions(+)
 create mode 100644 team.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash
No local changes to save
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash pop
No stash entries found.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash apply
No stash entries found.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash list
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git status
On branch dev
Your branch is ahead of 'origin/dev' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git reset --hard
>>
HEAD is now at d19df2b add team.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git status
>>
On branch dev
Your branch is ahead of 'origin/dev' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add home.html about.html team.html
>>
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add home.html about.html team.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "Add initial HTML pages"
On branch dev
Your branch is ahead of 'origin/dev' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash pop
No stash entries found.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash show -p | git apply
>>
No stash entries found.
error: No valid patches in input (allow with "--allow-empty")
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git status
>>
On branch dev
Your branch is ahead of 'origin/dev' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash apply
No stash entries found.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git status
>>
On branch dev
Your branch is ahead of 'origin/dev' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> ls


    Directory: C:\Users\Green
    Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---l        12/18/2024   3:10 PM            243 about.html
-a---l        12/18/2024   3:09 PM            242 home.html
-a---l        12/18/2024   2:36 PM             52 index.html
-a---l        12/18/2024   3:06 PM           1080 README.md
-a---l        12/18/2024   3:11 PM            242 team.html


PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (9/9), 938 bytes | 156.00 KiB/s, done.
Total 9 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), done.
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
   b2013b6..d19df2b  dev -> dev
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git satus
git: 'satus' is not a git command. See 'git --help'.

The most similar command is
        status
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
```
