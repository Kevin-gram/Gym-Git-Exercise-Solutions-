# Gym-Exercise-





The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Solutions (dev)
$ cd ..

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects (dev)
$ Gym-Git-Exercise-Solutions/
bash: Gym-Git-Exercise-Solutions/: Is a directory

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects (dev)
$ cd Gym-Git-Exercise-Solutions/

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (master)
$ echo "# Gym-Exercise-" >> README.md

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (master)
$ git commit -m "first commit"
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (master)
$ git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (master)
$ git commit -m "first commit"
[master (root-commit) 265d490] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (master)
$ git branch -M main

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git remote add origin https://github.com/Kevin-gram/Gym-Exercise-.git
error: remote origin already exists.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git push -u origin main
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git pull
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), 2.40 KiB | 55.00 KiB/s, done.
From https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-
 * [new branch]      main       -> origin/main
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git push -u origin main
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git pull https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git  main
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (1/1), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 932 bytes | 35.00 KiB/s, done.
From https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-
 * branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ ls
README.md

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ cd ..

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects (dev)
$ cd Solutions/

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Solutions (dev)
$ git branch test

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Solutions (dev)
$ git checkout test
Switched to branch 'test'

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Solutions (test)
$ git checkout dev
Switched to branch 'dev'

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Solutions (dev)
$ git branch -d test
Deleted branch test (was d9a4bb7).

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Solutions (dev)



////////////// bundel 1 eercise 2/////////////////////////////////////


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ vi home.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$  git add home.html
warning: in the working copy of 'home.html', LF will be replaced by CRLF the next time Git touches it

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git stash
Saved working directory and index state WIP on main: d89dec7 exercise 1 bundel 1

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ vi about.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$  git add about.html
warning: in the working copy of 'about.html', LF will be replaced by CRLF the next time Git touches it

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git stash
Saved working directory and index state WIP on main: d89dec7 exercise 1 bundel 1

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ vi team.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git stash list
stash@{0}: WIP on main: d89dec7 exercise 1 bundel 1
stash@{1}: WIP on main: d89dec7 exercise 1 bundel 1

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git add team.html
warning: in the working copy of 'team.html', LF will be replaced by CRLF the next time Git touches it

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git stash
Saved working directory and index state WIP on main: d89dec7 exercise 1 bundel 1

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git stash list
stash@{0}: WIP on main: d89dec7 exercise 1 bundel 1
stash@{1}: WIP on main: d89dec7 exercise 1 bundel 1
stash@{2}: WIP on main: d89dec7 exercise 1 bundel 1

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git stash pop stash@{1}
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (4ce4ee347831c2c46175a72ad7a04ce7f569195e)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git stash  pop stash@{1}
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (8327e4e0d10ec9587beab88d7d82788adf45ef49)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git add --all

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git commit -m"ho& about us page "
[main c0b61e3] ho& about us page
 2 files changed, 55 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 629 bytes | 157.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
   d89dec7..c0b61e3  main -> main

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git stash list
stash@{0}: WIP on main: d89dec7 exercise 1 bundel 1

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git stash list
stash@{0}: WIP on main: d89dec7 exercise 1 bundel 1

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git stash pop stash@{0}
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped stash@{0} (f5491f89762733c5c6a5beda36cb3d3323cda9bf)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git reset --hard
HEAD is now at c0b61e3 ho& about us page

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

//////////////////bundel 2 exercise 1///////////////////////////

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git commit -m"bundel 1 exercise 2"
[main 081580f] bundel 1 exercise 2
 1 file changed, 143 insertions(+)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.09 KiB | 2.09 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
   c0b61e3..081580f  main -> main

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git branch ft/bundle-2

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git checkout dev
Switched to branch 'dev'

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (dev)
$ ls
README.md  about.html  home.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (dev)
$ vi services.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (dev)
$ rm -r services.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (dev)
$ ls
README.md  about.html  home.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (dev)
$ git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ vi services.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git status
On branch ft/bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        services.html

nothing added to commit but untracked files present (use "git add" to track)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ vi services.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git add .
warning: in the working copy of 'services.html', LF will be replaced by CRLF the next time Git touches it

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git add services.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git commit -m"bundel 2"
[ft/bundle-2 8ffb5c5] bundel 2
 1 file changed, 22 insertions(+)
 create mode 100644 services.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/bundle-2)
$  git push --set-upstream origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 617 bytes | 617.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-/pull/new/ft/bundle-2
remote:
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/bundle-2)
$


/////////////////////// Bundel4 exercise 1//////////////


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git remote add git-copy  https://github.com/Kevin-gram/Gym-Exercise-.git

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git remote
git-copy
origin

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ vi home.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git commit -m"Editing the home page !!!"
git commit -m"Editing the home page git add .!"
[main 270b99f] Editing the home page git add .!
 1 file changed, 1 insertion(+), 1 deletion(-)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git push origin
fatal: unable to access 'https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git/': Could not resolve host: github.com

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git push origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 305 bytes | 305.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
   2dd984c..270b99f  main -> main

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git push git-copy
To https://github.com/Kevin-gram/Gym-Exercise-.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Kevin-gram/Gym-Exercise-.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git pull git-copy
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 213 bytes | 15.00 KiB/s, done.
From https://github.com/Kevin-gram/Gym-Exercise-
 * [new branch]      main       -> git-copy/main
You asked to pull from the remote 'git-copy', but did not specify
a branch. Because this is not the default configured remote
for your current branch, you must specify a branch on the command line.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git push --force git-copy
Enumerating objects: 38, done.
Counting objects: 100% (38/38), done.
Delta compression using up to 4 threads
Compressing objects: 100% (30/30), done.
Writing objects: 100% (38/38), 9.84 KiB | 1007.00 KiB/s, done.
Total 38 (delta 11), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (11/11), done.
To https://github.com/Kevin-gram/Gym-Exercise-.git
 + d9a4bb7...270b99f main -> main (forced update)



///////////////////Bundel 5 exercise 1///////////////


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git branch ft/footer

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git chechout ft/footer
git: 'chechout' is not a git command. See 'git --help'.

The most similar command is
        checkout

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git checkout ft/footer
Switched to branch 'ft/footer'
M       README.md

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/footer)
$ vi home.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/footer)
$  git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/footer)
$ git commit -m"new branch ft/footer"
[ft/footer d747347] new branch ft/footer
 2 files changed, 78 insertions(+), 1 deletion(-)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/footer)
$ git push
fatal: The current branch ft/footer has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/footer

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/footer)
$ git push --set-upstream origin ft/footer
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.08 KiB | 553.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-/pull/new/ft/footer
remote:
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
 * [new branch]      ft/footer -> ft/footer
branch 'ft/footer' set up to track 'origin/ft/footer'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/footer)
$ vi home.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/footer)
$  git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/footer)
$ git push
Everything up-to-date

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/footer)
$ vi home.html
Z
The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/footer)
$  git add  home.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/footer)
$ git commit -m"new branch ft/footer SECOMD CHANGES "
[ft/footer a6102ab] new branch ft/footer SECOMD CHANGES
 1 file changed, 1 insertion(+), 1 deletion(-)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/footer)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 343 bytes | 343.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
   d747347..a6102ab  ft/footer -> ft/footer

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/footer)
$  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git branch ft/squashing

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git merge --squash ft/f
ft/faq-page   ft/footer

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git merge --squash ft/footer
Updating 270b99f..a6102ab
Fast-forward
Squash commit -- not updating HEAD
 README.md | 77 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 home.html |  2 +-
 2 files changed, 78 insertions(+), 1 deletion(-)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git commit -m"footer changes squashing"
[main 5503693] footer changes squashing
 2 files changed, 78 insertions(+), 1 deletion(-)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git checkout ft/s
ft/service-redesign   ft/squashing

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git checkout ft/squashing
Switched to branch 'ft/squashing'

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ git merge --squash ft/footer
Updating 270b99f..a6102ab
Fast-forward
Squash commit -- not updating HEAD
 README.md | 77 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 home.html |  2 +-
 2 files changed, 78 insertions(+), 1 deletion(-)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ git commit -m"footer changes squashing"
[ft/squashing 3f1d969] footer changes squashing
 2 files changed, 78 insertions(+), 1 deletion(-)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ git push origin ft/squashing
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.10 KiB | 564.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-/pull/new/ft/squashing
remote:
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
 * [new branch]      ft/squashing -> ft/squashing

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> ft/squashing


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ git pull origin ft/squashing
From https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-
 * branch            ft/squashing -> FETCH_HEAD
Already up to date.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ ls
README.md  about.html  imdex.html.html  services.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ ls
README.md  about.html  index.html.html  services.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ ls
README.md  about.html  index.html.html  services.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ ls
README.md  about.html  index.html.html  services.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ mv index.html.html  index.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ ls
README.md  about.html  index.html  services.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ git add index.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ git status
On branch ft/squashing
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        renamed:    home.html -> index.html


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ git commit -m"reanming hoe to index.html"
[ft/squashing eef632e] reanming hoe to index.html
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename home.html => index.html (100%)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ git push
fatal: The current branch ft/squashing has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/squashing

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ ^C

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ git push --set-upstream origin ft/squashing
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 246 bytes | 246.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
   3f1d969..eef632e  ft/squashing -> ft/squashing
branch 'ft/squashing' set up to track 'origin/ft/squashing'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/squashing)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ mv home.html  index.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git commit -m"reanaming hoe to index.html"
[main 4f75d3f] reanaming hoe to index.html
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename home.html => index.html (100%)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.52 KiB | 777.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
   270b99f..4f75d3f  main -> main

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ vi index.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git commit -m"reanaming hoe to index.html"
[main 96c8689] reanaming hoe to index.html
 1 file changed, 2 insertions(+), 2 deletions(-)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 304 bytes | 304.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
   4f75d3f..96c8689  ma
   in -> main
/////////////////////bundel 5 exercise 2////////////


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git clone https://github.com/Kevin-gram/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (10/10), done.
error: RPC failed; curl 56 OpenSSL SSL_read: SSL_ERROR_SYSCALL, errno 0
error: 4044 bytes of body are still expected
fetch-pack: unexpected disconnect while reading sideband packet
fatal: early EOF
fatal: fetch-pack: invalid index-pack output

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git clone https://github.com/Kevin-gram/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 93
Receiving objects: 100% (107/107), 1.95 MiB | 2.17 MiB/s, done.
Resolving deltas: 100% (5/5), done.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ cd git-cafe-exercise/

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ ls
README.md  css/     index-1.html  index-3.html  index.html
bat/       images/  index-2.html  index-4.html  js/

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ vi index.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git commit -m 'changing index.html file '
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git commit -m 'changing index.html file '
[main bad5552] changing index.html file
 1 file changed, 2 insertions(+), 2 deletions(-)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 333 bytes | 333.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Kevin-gram/git-cafe-exercise.git
   d1d3f9c..bad5552  main -> main


////////////////bundel 5 exercise 2//////////////



The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git clone https://github.com/Kevin-gram/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (10/10), done.
error: RPC failed; curl 56 OpenSSL SSL_read: SSL_ERROR_SYSCALL, errno 0
error: 4044 bytes of body are still expected
fetch-pack: unexpected disconnect while reading sideband packet
fatal: early EOF
fatal: fetch-pack: invalid index-pack output

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git clone https://github.com/Kevin-gram/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 93
Receiving objects: 100% (107/107), 1.95 MiB | 2.17 MiB/s, done.
Resolving deltas: 100% (5/5), done.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ cd git-cafe-exercise/

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ ls
README.md  css/     index-1.html  index-3.html  index.html
bat/       images/  index-2.html  index-4.html  js/

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ vi index.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git commit -m 'changing index.html file '
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git commit -m 'changing index.html file '
[main bad5552] changing index.html file
 1 file changed, 2 insertions(+), 2 deletions(-)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 333 bytes | 333.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Kevin-gram/git-cafe-exercise.git
   d1d3f9c..bad5552  main -> main

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions/git-cafe-exercise (main)
$ cd ..

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ vi README.md

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git add .
warning: adding embedded git repository: git-cafe-exercise
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> git-cafe-exercise
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached git-cafe-exercise
hint:
hint: See "git help submodule" for more information.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git rm -r git-cafe-exercise/
fatal: could not lookup name for submodule 'git-cafe-exercise'

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ cd ..

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects (dev)
$ git clone https://github.com/Kevin-gram/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
fatal: unable to access 'https://github.com/Kevin-gram/git-cafe-exercise.git/': Recv failure: Connection was reset

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects (dev)
$ git clone https://github.com/Kevin-gram/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 110, done.
remote: Counting objects: 100% (17/17), done.
remote: Compressing objects: 100% (12/12), done.
error: RPC failed; curl 92 HTTP/2 stream 5 was not closed cleanly: CANCEL (err 8)
error: 6568 bytes of body are still expected
fetch-pack: unexpected disconnect while reading sideband packet
fatal: early EOF
fatal: fetch-pack: invalid index-pack output

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects (dev)
$ git clone https://github.com/Kevin-gram/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 110, done.
remote: Counting objects: 100% (17/17), done.
remote: Compressing objects: 100% (12/12), done.
remote: Total 110 (delta 7), reused 6 (delta 5), pack-reused 93
Receiving objects: 100% (110/110), 1.95 MiB | 199.00 KiB/s, done.
Resolving deltas: 100% (7/7), done.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects (dev)
$ vi index.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects (dev)
$ cd git-cafe-exercise/

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/git-cafe-exercise (main)
$ vi index.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/git-cafe-exercise (main)
$ git commit -m 'changing index.html file '
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/git-cafe-exercise (main)
$ git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/git-cafe-exercise (main)
$ git commit -m 'changing index.html file '
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

