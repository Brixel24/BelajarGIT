# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT

asus@LAPTOP-946LNVOU MINGW64 ~ (main)
$ git config --global user.email "clarkmetthew967@gmail.com"

asus@LAPTOP-946LNVOU MINGW64 ~ (main)
$ git init
Reinitialized existing Git repository in C:/Users/asus/.git/

asus@LAPTOP-946LNVOU MINGW64 ~ (main)
$ cd "C:\Users\asus\Pemograman Web"

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web (main)
$ git clone https://github.com/Brixel24/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 9 (delta 1), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (9/9), done.
Resolving deltas: 100% (1/1), done.

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web (main)
$ cd belajarGIT

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch Tugas-git

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch
  Tugas-git
* main

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-git)
$ echo "test git" >> Tugas-git.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
warning: in the working copy of 'Tugas-git.txt', LF will be replaced by CRLF the next time Git touches it

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan perubahan pada Tugas-git.txt"
[Tugas-git 6644812] Menambahkan perubahan pada Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git merge Tugas-git
Updating 373d0bf..6644812
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 312 bytes | 312.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Brixel24/belajarGIT.git
   373d0bf..6644812  main -> main

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch Tugas-html

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-html)
$ echo "test html" >> Tugas-html.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
warning: in the working copy of 'Tugas-html.txt', LF will be replaced by CRLF the next time Git touches it

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
[Tugas-html 470be4b] Menambahkan perubahan pada Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git merge Tugas-html
Updating 6644812..470be4b
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 346 bytes | 346.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Brixel24/belajarGIT.git
   6644812..470be4b  main -> main

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch Tugas-css

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-css)
$ echo "test css" >> Tugas-css.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
warning: in the working copy of 'Tugas-css.txt', LF will be replaced by CRLF the next time Git touches it

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan perubahan pada Tugas-css.txt"
[Tugas-css 1cb3f83] Menambahkan perubahan pada Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git merge Tugas-css
Updating 470be4b..1cb3f83
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 374 bytes | 374.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Brixel24/belajarGIT.git
   470be4b..1cb3f83  main -> main

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch Tugas-js

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* main

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-js)
$ echo "test js" >> Tugas-js.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-js)
$ git add Tugas-js.txt
warning: in the working copy of 'Tugas-js.txt', LF will be replaced by CRLF the next time Git touches it

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan perubahan pada Tugas-js.txt"
[Tugas-js 25d7411] Menambahkan perubahan pada Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git merge Tugas-js
Updating 1cb3f83..25d7411
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 309 bytes | 309.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Brixel24/belajarGIT.git
   1cb3f83..25d7411  main -> main

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch Tugas-midProject

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* main

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-midProject)
$ echo "test midProject" >> Tugas-midProject.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt
warning: in the working copy of 'Tugas-midProject.txt', LF will be replaced by CRLF the next time Git touches it

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 35e1aad] Menambahkan file Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan perubahan pada Tugas-midProject.txt"
On branch Tugas-midProject
nothing to commit, working tree clean

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git merge Tugas-midProject
Updating 25d7411..35e1aad
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 323 bytes | 323.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Brixel24/belajarGIT.git
   25d7411..35e1aad  main -> main

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch Tugas-php

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-php)
$ echo "test php" >> Tugas-php.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-php)
$ git add Tugas-php.txt
warning: in the working copy of 'Tugas-php.txt', LF will be replaced by CRLF the next time Git touches it

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan perubahan pada Tugas-php.txt"
[Tugas-php adf96ad] Menambahkan perubahan pada Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git merge Tugas-php
Updating 35e1aad..adf96ad
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 308 bytes | 308.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Brixel24/belajarGIT.git
   35e1aad..adf96ad  main -> main

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch Tugas-finalProject

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-finalProject)
$ echo "test finalProject" >> Tugas-finalProject.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt
warning: in the working copy of 'Tugas-finalProject.txt', LF will be replaced by CRLF the next time Git touches it

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan perubahan pada Tugas-finalProject.txt"
[Tugas-finalProject 964df78] Menambahkan perubahan pada Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git merge Tugas-finalProject
Updating adf96ad..964df78
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

asus@LAPTOP-946LNVOU MINGW64 ~/Pemograman Web/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 326 bytes | 326.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Brixel24/belajarGIT.git
   adf96ad..964df78  main -> main
