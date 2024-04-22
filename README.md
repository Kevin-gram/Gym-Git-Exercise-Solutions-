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



The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git checkout ft/team-page
error: pathspec 'ft/team-page' did not match any file(s) known to git

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git branch ft/team-page

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
M       README.md

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/team-page)
$ vi team

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/team-page)
$ vi team

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/team-page)
$ git add .
warning: in the working copy of 'team', LF will be replaced by CRLF the next time Git touches it

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/team-page)
$ git commit -m'team.html page '
[ft/team-page 0500274] team.html page
 2 files changed, 99 insertions(+)
 create mode 100644 team

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/team-page)
$ git push --set-upstream origin ft/team-page
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.17 KiB | 1.17 MiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-/pull/new/ft/team-page
remote:
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git branch ft/contact-page

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/team-page)
$ git log
commit 05002746c969b73965195bda7f3585f539440b91 (HEAD -> ft/team-page, origin/ft/team-page)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 17:49:09 2024 +0200

    team.html page

commit 2dd984cece9dc2d28c58aa373d3a540c6c5e892e (origin/main, main, ft/contact-page)
Merge: 61ba0f7 faeb0cc
Author: Kevin_Nyiringango <116556392+Kevin-gram@users.noreply.github.com>
Date:   Mon Apr 22 17:19:25 2024 +0200

    Merge pull request #3 from Kevin-gram/ft/bundle-2

    bundel 2 EXERCISE 1

commit 61ba0f77ce49c7831812c0ff4bee3f8562131c9c
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 17:09:48 2024 +0200

    editing the services IN MAIN branch

commit faeb0cc431c0f687021464c860dc0ded1c28e267 (origin/ft/bundle-2, ft/bundle-2)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 16:45:41 2024 +0200

    bundel 2 EXERCISE 1

commit 3a98acd433900307a95e05780b6058ba9e7100d3
Merge: 081580f 8ffb5c5
Author: MANZI Mike <48416679+MikeManzi@users.noreply.github.com>
Date:   Mon Apr 22 16:38:41 2024 +0200

    Merge pull request #1 from Kevin-gram/ft/bundle-2

    bundel 2

commit 8ffb5c567013cb7ac9e662701c76dcf61b4efb41
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 16:26:25 2024 +0200

    bundel 2

commit 081580f8273a735b4223a95a29784d49761bdf8d
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 16:11:59 2024 +0200

    bundel 1 exercise 2

commit c0b61e33fc9a48d7f421f0ba5b96d8086735a375 (dev)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 15:51:01 2024 +0200

    ho& about us page

commit d89dec71b1cc4efb2c4b992a38c545eb55931e0d
Merge: 725597e cdc1ed4
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 14:38:18 2024 +0200


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git cherry-pick 05002746c969b73965195bda7f3585f539440b91
[ft/contact-page 634d797] team.html page
 Date: Mon Apr 22 17:49:09 2024 +0200
 2 files changed, 99 insertions(+)
 create mode 100644 team

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/contact-page)
$ ls
README.md  about.html  home.html  services.html  team

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/contact-page)
$ vi contact.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git add .
warning: in the working copy of 'contact.html', LF will be replaced by CRLF the next time Git touches it

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git commit -m"creating contact page"
[ft/contact-page 26adcd2] creating contact page
 1 file changed, 27 insertions(+)
 create mode 100644 contact.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git push --set-upstream origin ft/contact-page
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 1.44 KiB | 739.00 KiB/s, done.
Total 7 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-/pull/new/ft/contact-page
remote:
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git branch ft/faq-page

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git checkout ft/faq-page
Switched to branch 'ft/faq-page'

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ vi faq.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git add .
warning: in the working copy of 'faq.html', LF will be replaced by CRLF the next time Git touches it

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git commit -m"faqhtml"
[ft/faq-page 54526ec] faqhtml
 1 file changed, 23 insertions(+)
 create mode 100644 faq.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git push
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git push --set-upstream origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 551 bytes | 551.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-/pull/new/ft/faq-page
remote:
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git log
commit 54526ece8b8e41c428ef446ad7cde2134e9d9aab (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 19:59:46 2024 +0200

    faqhtml

commit 26adcd2e04e5f0ef402813a7b7e6462c508199cd (origin/ft/contact-page, ft/contact-page)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 19:45:53 2024 +0200

    creating contact page

commit 634d797bff32e71616056f9369f7dffb0ca31eee
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 17:49:09 2024 +0200

    team.html page

commit 2dd984cece9dc2d28c58aa373d3a540c6c5e892e (origin/main, main)
Merge: 61ba0f7 faeb0cc
Author: Kevin_Nyiringango <116556392+Kevin-gram@users.noreply.github.com>
Date:   Mon Apr 22 17:19:25 2024 +0200

    Merge pull request #3 from Kevin-gram/ft/bundle-2

    bundel 2 EXERCISE 1

commit 61ba0f77ce49c7831812c0ff4bee3f8562131c9c
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 17:09:48 2024 +0200

    editing the services IN MAIN branch

commit faeb0cc431c0f687021464c860dc0ded1c28e267 (origin/ft/bundle-2, ft/bundle-2)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 16:45:41 2024 +0200

    bundel 2 EXERCISE 1

commit 3a98acd433900307a95e05780b6058ba9e7100d3
Merge: 081580f 8ffb5c5
Author: MANZI Mike <48416679+MikeManzi@users.noreply.github.com>
Date:   Mon Apr 22 16:38:41 2024 +0200

    Merge pull request #1 from Kevin-gram/ft/bundle-2

    bundel 2

commit 8ffb5c567013cb7ac9e662701c76dcf61b4efb41
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 16:26:25 2024 +0200

    bundel 2

commit 081580f8273a735b4223a95a29784d49761bdf8d
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 16:11:59 2024 +0200


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git revert 54526ece8b8e41c428ef446ad7cde2134e9d9aab
[ft/faq-page 0593f5a] Revert "faqhtml"
 1 file changed, 23 deletions(-)
 delete mode 100644 faq.html

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git log
commit 0593f5ab49521d301e62c727410feed1e776770c (HEAD -> ft/faq-page)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 20:05:05 2024 +0200

    Revert "faqhtml"

    This reverts commit 54526ece8b8e41c428ef446ad7cde2134e9d9aab.

commit 54526ece8b8e41c428ef446ad7cde2134e9d9aab (origin/ft/faq-page)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 19:59:46 2024 +0200

    faqhtml

commit 26adcd2e04e5f0ef402813a7b7e6462c508199cd (origin/ft/contact-page, ft/contact-page)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 19:45:53 2024 +0200

    creating contact page

commit 634d797bff32e71616056f9369f7dffb0ca31eee
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 17:49:09 2024 +0200

    team.html page

commit 2dd984cece9dc2d28c58aa373d3a540c6c5e892e (origin/main, main)
Merge: 61ba0f7 faeb0cc
Author: Kevin_Nyiringango <116556392+Kevin-gram@users.noreply.github.com>
Date:   Mon Apr 22 17:19:25 2024 +0200

    Merge pull request #3 from Kevin-gram/ft/bundle-2

    bundel 2 EXERCISE 1

commit 61ba0f77ce49c7831812c0ff4bee3f8562131c9c
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 17:09:48 2024 +0200

    editing the services IN MAIN branch

commit faeb0cc431c0f687021464c860dc0ded1c28e267 (origin/ft/bundle-2, ft/bundle-2)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon Apr 22 16:45:41 2024 +0200

    bundel 2 EXERCISE 1

commit 3a98acd433900307a95e05780b6058ba9e7100d3
Merge: 081580f 8ffb5c5
Author: MANZI Mike <48416679+MikeManzi@users.noreply.github.com>
Date:   Mon Apr 22 16:38:41 2024 +0200

    Merge pull request #1 from Kevin-gram/ft/bundle-2

    bundel 2

commit 8ffb5c567013cb7ac9e662701c76dcf61b4efb41
Author: kevin-gram <k.nyiringan@alustudent.com>

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ ls
README.md  about.html  contact.html  home.html  services.html  team

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ vi team

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git commit -m"reverting changes "
On branch ft/faq-page
Your branch is ahead of 'origin/ft/faq-page' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 255 bytes | 255.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
   54526ec..0593f5a  ft/faq-page -> ft/faq-page


//////////////////bundel 3 exercise 2//////////////////////


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/fa
$ git branch ft/faq-page
fatal: a branch named 'ft/faq-page' already exists

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git branch ft/home-page-redesign

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
M       README.md

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        README.md
Please commit your changes or stash them before you switch branches.
Aborting

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git commit -m "ft/home-page-redesign"
[ft/home-page-redesign 61abd2d] ft/home-page-redesign
 1 file changed, 398 insertions(+)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git push
fatal: The current branch ft/home-page-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/home-page-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git push --set-upstream origin ft/home-page-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.32 KiB | 2.32 MiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-/pull/new/ft/home-page-redesign
remote:
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git commit -m "ft/home-page-redesign"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
Your branch is up to date with 'origin/ft/home-page-redesign'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git rebase main
Current branch ft/home-page-redesign is up to date.

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ ls
README.md  about.html  contact.html  home.html  services.html  team

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ vi home.html
Z
The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git add .

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git commit -m "rebase"
[ft/home-page-redesign 80a855e] rebase
 1 file changed, 2 insertions(+), 2 deletions(-)

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Documents/projects/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 291 bytes | 291.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions-.git
   61abd2d..80a855e  ft/home-page-redesign -> ft/home-page-redesign

