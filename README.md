# Gym-Git-Exercise-Solutions-


The Gym@DESKTOP-FTJIN5G MINGW64 ~
$ echo "# Gym-Exercise-" >> README.md

The Gym@DESKTOP-FTJIN5G MINGW64 ~
$ git init
Initialized empty Git repository in C:/Users/The Gym/.git/

The Gym@DESKTOP-FTJIN5G MINGW64 ~ (master)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

The Gym@DESKTOP-FTJIN5G MINGW64 ~ (master)
$ git commit -m "first commit"
[master (root-commit) d9a4bb7] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

The Gym@DESKTOP-FTJIN5G MINGW64 ~ (master)
$ git branch -M main

The Gym@DESKTOP-FTJIN5G MINGW64 ~ (main)
$ git remote add origin https://github.com/Kevin-gram/Gym-Exercise-.git

The Gym@DESKTOP-FTJIN5G MINGW64 ~ (main)
$ git push -u origin main

fatal: unable to access 'https://github.com/Kevin-gram/Gym-Exercise-.git/': Recv failure: Connection was reset
The Gym@DESKTOP-FTJIN5G MINGW64 ~ (main)
$ git push -u origin main

fatal: unable to access 'https://github.com/Kevin-gram/Gym-Exercise-.git/': OpenSSL SSL_read: SSL_ERROR_SYSCALL, errno 0

The Gym@DESKTOP-FTJIN5G MINGW64 ~ (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 233 bytes | 233.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Kevin-gram/Gym-Exercise-.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

The Gym@DESKTOP-FTJIN5G MINGW64 ~ (main)
$ git branch dev

The Gym@DESKTOP-FTJIN5G MINGW64 ~ (main)
$ git checkout dev
Switched to branch 'dev'

The Gym@DESKTOP-FTJIN5G MINGW64 ~ (dev)
$ git branch test

The Gym@DESKTOP-FTJIN5G MINGW64 ~ (dev)
$ git checkout test
Switched to branch 'test'

The Gym@DESKTOP-FTJIN5G MINGW64 ~ (test)
$ git checkout dev
Switched to branch 'dev'

The Gym@DESKTOP-FTJIN5G MINGW64 ~ (dev)
$ git branch -d test
Deleted branch test (was d9a4bb7).
