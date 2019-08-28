# My Website

This is the README.md file the Github repository my-website.

It was created using the ReText editor on my laptop and saved in the folder *site*. This site folder is a git repository on my laptop.

This *site* folder has a directory called *docs* off it. The *docs* directory has the website files.

The README.md was added to Github as follows:

```
(venv7) ian@X200:~/my-website/site$ ls
docs  README.md
(venv7) ian@X200:~/my-website/site$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md

nothing added to commit but untracked files present (use "git add" to track)
(venv7) ian@X200:~/my-website/site$ git add README.md
(venv7) ian@X200:~/my-website/site$ git commit -m "README.md added"
[master 9201620] README.md added
 1 file changed, 9 insertions(+)
 create mode 100644 README.md
(venv7) ian@X200:~/my-website/site$ git push -u origin master
Username for 'https://github.com': irsbugs
Password for 'https://irsbugs@github.com': 
Counting objects: 3, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 479 bytes | 479.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/irsbugs/my-website.git
   ea48278..9201620  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
(venv7) ian@X200:~/my-website/site$ 

```