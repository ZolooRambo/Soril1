"Git PR туршилт"

өөрчлөлт
LENOVO@Zolbayar MINGW64 ~ (masdter)
$ git clone https://github.com/ZolooRambo/Soril1.git
Cloning into 'Soril1'...
warning: You appear to have cloned an empty repository.

LENOVO@Zolbayar MINGW64 ~ (masdter)
$ cd Soril1

LENOVO@Zolbayar MINGW64 ~/Soril1 (main)
$ git init
Reinitialized existing Git repository in C:/Users/LENOVO/Soril1/.git/

LENOVO@Zolbayar MINGW64 ~/Soril1 (main)
$ code .

LENOVO@Zolbayar MINGW64 ~/Soril1 (main)
$ git add .

LENOVO@Zolbayar MINGW64 ~/Soril1 (main)
$ git commit -m "soril1 commit"
[main (root-commit) 1796de2] soril1 commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

LENOVO@Zolbayar MINGW64 ~/Soril1 (main)
$ git branch -M main

LENOVO@Zolbayar MINGW64 ~/Soril1 (main)
$ git remote add origin https://github.com/ZolooRambo/Soril1.git
error: remote origin already exists.

LENOVO@Zolbayar MINGW64 ~/Soril1 (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 240 bytes | 240.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ZolooRambo/Soril1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

LENOVO@Zolbayar MINGW64 ~/Soril1 (main)
$ echo "# Soril"> README.md

LENOVO@Zolbayar MINGW64 ~/Soril1 (main)
$ git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

LENOVO@Zolbayar MINGW64 ~/Soril1 (main)
$ git commit -m "soril"
[main 82077cd] soril
 1 file changed, 1 insertion(+), 1 deletion(-)

LENOVO@Zolbayar MINGW64 ~/Soril1 (main)
$ git branch feature-test

LENOVO@Zolbayar MINGW64 ~/Soril1 (main)
$ git checkout feature-test
Switched to branch 'feature-test'

LENOVO@Zolbayar MINGW64 ~/Soril1 (feature-test)
$ git add README.md

LENOVO@Zolbayar MINGW64 ~/Soril1 (feature-test)
$ git commit -m "Oorchlolt"
On branch feature-test
nothing to commit, working tree clean

LENOVO@Zolbayar MINGW64 ~/Soril1 (feature-test)
$ git commit -m "shinchlelt"
On branch feature-test
nothing to commit, working tree clean

LENOVO@Zolbayar MINGW64 ~/Soril1 (feature-test)
$ git add .

LENOVO@Zolbayar MINGW64 ~/Soril1 (feature-test)
$ git commit -m "shinchlelt"
On branch feature-test
nothing to commit, working tree clean

LENOVO@Zolbayar MINGW64 ~/Soril1 (feature-test)
$ git commit -m "shinchlelt"
On branch feature-test
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

LENOVO@Zolbayar MINGW64 ~/Soril1 (feature-test)
$ git add .

LENOVO@Zolbayar MINGW64 ~/Soril1 (feature-test)
$ git commit -m "Shinchlelt"
[feature-test 4fa3f9b] Shinchlelt
 1 file changed, 3 insertions(+), 1 deletion(-)

LENOVO@Zolbayar MINGW64 ~/Soril1 (feature-test)
$ git push origin feature-test
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (6/6), 502 bytes | 251.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ZolooRambo/Soril1.git
   1796de2..4fa3f9b  feature-test -> feature-test

LENOVO@Zolbayar MINGW64 ~/Soril1 (feature-test)
$ ^C

LENOVO@Zolbayar MINGW64 ~/Soril1 (feature-test)
$
