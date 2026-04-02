AIML@mitm-aiml-007 MINGW64 ~
$ cd desktrop
bash: cd: desktrop: No such file or directory

AIML@mitm-aiml-007 MINGW64 ~
$ cd Desktop

AIML@mitm-aiml-007 MINGW64 ~/Desktop
$ cd devops_git_lab

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab
$ git init
Initialized empty Git repository in C:/Users/AIML/Desktop/devops_git_lab/.git/

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (master)
$ mkdir README.md

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (master)
$ mkdir devops_notes.txt

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (master)
$ git add .

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (master)
$ git commit -m "Initial commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'AIML@mitm-aiml-007.(none)')

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (master)
$ git config --global user.email "bhoomikasj1234@gmail.com"

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (master)
$ git add .

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (master)
$ git commit -m
error: switch `m' requires a value

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (master)
$ git commit -m "initial-commit"
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (master)
$ git branch -m Main

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (Main)
$ git remote add origin https://github.com/Bhoomikasj-20/devops_lab.git

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (Main)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Bhoomikasj-20/devops_lab.git'

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (Main)
$ git branch -m main

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Bhoomikasj-20/devops_lab.git'

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ git add .

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ git commit -m "Initial commit"
On branch main

Initial commit

nothing to commit (create/copy files and use "git add" to track)

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Bhoomikasj-20/devops_lab.git'

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ echo "# devops_git_lab" > README.md
bash: README.md: Is a directory

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ echo "devops_git_lab" > devops_notes.txt
bash: devops_notes.txt: Is a directory

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ rm -rf README.md/devops_notes.txt/

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ ls
README.md/  devops_notes.txt/

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ rm -rf README.md/devops_notes.txt/

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ rm -rf README.md devops_notes.txt

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ ls

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ echo "# DevOps Lab" > README.md

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ echo "DevOps notes" > devops_notes.txt

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ ls -l
total 2
-rw-r--r-- 1 AIML 197121 13 Apr  2 10:15 README.md
-rw-r--r-- 1 AIML 197121 13 Apr  2 10:15 devops_notes.txt

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'devops_notes.txt', LF will be replaced by CRLF the next time Git touches it

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ git commit -m "Initial commit"
[main (root-commit) 7fd7f57] Initial commit
 2 files changed, 2 insertions(+)
 create mode 100644 README.md
 create mode 100644 devops_notes.txt

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$ git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 20 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 293 bytes | 293.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Bhoomikasj-20/devops_lab.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

AIML@mitm-aiml-007 MINGW64 ~/Desktop/devops_git_lab (main)
$

