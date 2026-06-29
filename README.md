# git-cafe-exercise
#Bundle 5

```bash
applelab@uok-i-mac22 ~ % git clone https://github.com/fatimabobegoto-collab/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 92 (from 1)
Receiving objects: 100% (107/107), 1.95 MiB | 574.00 KiB/s, done.
Resolving deltas: 100% (5/5), done.
applelab@uok-i-mac22 ~ % ls
apple.html              Documents               Library                 Pictures
Applications            Downloads               mhealth                 Public
Desktop                 git-cafe-exercise       Movies
Development             index.html              Music
applelab@uok-i-mac22 ~ % cd git-cafe-exercise
applelab@uok-i-mac22 git-cafe-exercise % ls -a
.               bat             index-1.html    index-4.html    README.md
..              css             index-2.html    index.html
.git            images          index-3.html    js
applelab@uok-i-mac22 git-cafe-exercise % nano index.html
applelab@uok-i-mac22 git-cafe-exercise % git add index.htmljm
fatal: pathspec 'index.htmljm' did not match any files
applelab@uok-i-mac22 git-cafe-exercise % git add index.html  
applelab@uok-i-mac22 git-cafe-exercise % git commit -m "correction: place -> restaurant"
[main d209111] correction: place -> restaurant
 1 file changed, 288 insertions(+), 288 deletions(-)
applelab@uok-i-mac22 git-cafe-exercise % git remote -v
origin  https://github.com/fatimabobegoto-collab/git-cafe-exercise.git (fetch)
origin  https://github.com/fatimabobegoto-collab/git-cafe-exercise.git (push)
applelab@uok-i-mac22 git-cafe-exercise % git push    
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.36 KiB | 1.36 MiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/fatimabobegoto-collab/git-cafe-exercise.git
   d1d3f9c..d209111  main -> main
applelab@uok-i-mac22 git-cafe-exercise % 
```
