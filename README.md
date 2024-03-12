Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT:

ASUS@DESKTOP-S1JB6N2 MINGW64 ~
$ cd "L:\Campus\College\Semester 4\Pemrograman Web"

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web
$ git clone https://github.com/jennilaluyan/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web
$ git branch Tugas-git
fatal: not a git repository (or any of the parent directories): .git

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web
$ git branch

fatal: not a git repository (or any of the parent directories): .git

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web
$ cd "L:\Campus\College\Semester 4\Pemrograman Web\belajarGIT"

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch
* main

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-git

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-html

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-css

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-js

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-midProject

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-php

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git branch Tugas-finalProject

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git switch Tugas-git
Switched to branch 'Tugas-git'

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git branch
  Tugas-css
  Tugas-finalProject
* Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
  main

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
fatal: pathspec 'Tugas-git.txt' did not match any files

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ cd "L:\Campus\College\Semester 4\Pemrograman Web\belajarGIT"

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
fatal: pathspec 'Tugas-git.txt' did not match any files

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git branch
  Tugas-css
  Tugas-finalProject
* Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
  main

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
fatal: pathspec 'Tugas-git.txt' did not match any files

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-css.txt.txt
        Tugas-finalProject.txt.txt
        Tugas-git.txt.txt
        Tugas-html.txt.txt
        Tugas-js.txt.txt
        Tugas-midProject.txt.txt
        Tugas-php.txt.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
fatal: pathspec 'Tugas-git.txt' did not match any files

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-css.txt
        Tugas-finalProject.txt
        Tugas-html.txt
        Tugas-js.txt
        Tugas-midProject.txt
        Tugas-php.txt


ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt


ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git commit -m "berhasil add git"
[Tugas-git b6ff79b] berhasil add git
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-git)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-git
Updating 6372e1b..b6ff79b
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 298 bytes | 298.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/jennilaluyan/belajarGIT.git
   6372e1b..b6ff79b  main -> main

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git add Tugas-html.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git commit -m "berhasil add html"
[main 9bc8690] berhasil add html
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git switch main
Already on 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-html
Already up to date.

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-html
Already up to date.

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git switch Tugas-html
Switched to branch 'Tugas-html'

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git add Tugas.html
fatal: pathspec 'Tugas.html' did not match any files

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git add Tugas-html
fatal: pathspec 'Tugas-html' did not match any files

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git commit -m "berhasil add html"
[Tugas-html 71e1361] berhasil add html
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-html)
$ git switch main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-html
Merge made by the 'ort' strategy.

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 16 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 641 bytes | 641.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/jennilaluyan/belajarGIT.git
   b6ff79b..c4337e8  main -> main

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git switch Tugas-css
Switched to branch 'Tugas-css'

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-css)
$ git commit -m "berhasil add css"
[Tugas-css ac077b5] berhasil add css
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-css)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-css
Merge made by the 'ort' strategy.
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 573 bytes | 573.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/jennilaluyan/belajarGIT.git
   c4337e8..ed897da  main -> main

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git switch Tugas-js
Switched to branch 'Tugas-js'

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-js)
$ git switch main
Switched to branch 'main'
A       Tugas-js.txt
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git switch Tugas-js
Switched to branch 'Tugas-js'
A       Tugas-js.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-js)
$ git commit -m "berhasil add js"
[Tugas-js 97240fd] berhasil add js
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-js)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-js
Merge made by the 'ort' strategy.
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 507 bytes | 507.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/jennilaluyan/belajarGIT.git
   ed897da..60a88bc  main -> main

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git switch Tugas-midProject
Switched to branch 'Tugas-midProject'

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git commit -m "berhasil add midProject"
[Tugas-midProject 8dd8886] berhasil add midProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-midProject)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-midProject
Merge made by the 'ort' strategy.
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 524 bytes | 524.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/jennilaluyan/belajarGIT.git
   60a88bc..de99c8f  main -> main

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git switch Tugas-php
Switched to branch 'Tugas-php'

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-php)
$ git commit -m "berhasil add php"
[Tugas-php 36e5c30] berhasil add php
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-php)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-php
Merge made by the 'ort' strategy.
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 507 bytes | 507.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/jennilaluyan/belajarGIT.git
   de99c8f..1287319  main -> main

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git switch Tugas-finalProject
Switched to branch 'Tugas-finalProject'

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git commit -m "berhasil add finalProject"
[Tugas-finalProject 25e163c] berhasil add finalProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (Tugas-finalProject)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git merge Tugas-finalProject
Merge made by the 'ort' strategy.
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 533 bytes | 533.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/jennilaluyan/belajarGIT.git
   1287319..209ae01  main -> main

ASUS@DESKTOP-S1JB6N2 MINGW64 /l/Campus/College/Semester 4/Pemrograman Web/belajarGIT (main)
$

