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


///////////////// BUNDEL 2 EXERCISE 2////////////////////


$  git push --set-upstream origin ft/service-redesign

Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 305 bytes | 305.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-/pull/new/ft/service-redesign
remote:
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ vi services.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git commit -m 'editing the services IN MAIN branch'
[main 61ba0f7] editing the services IN MAIN branch
 1 file changed, 1 insertion(+), 1 deletion(-)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 320 bytes | 320.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
   3a98acd..61ba0f7  main -> main

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git commit -m 'editing the services IN MAIN branch'
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (2/2), 972 bytes | 48.00 KiB/s, done.
From https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-
   61ba0f7..2dd984c  main       -> origin/main
Updating 61ba0f7..2dd984c
Fast-forward
 README.md | 105 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 105 insertions(+)

///////////////Bundel 3 exercise 1////////////


