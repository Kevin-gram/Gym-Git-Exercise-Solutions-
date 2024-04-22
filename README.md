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
