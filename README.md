# basic1

int i=0;

C:\Users\user>git clone https://github.com/Ilhwan123/basic1.git
Cloning into 'basic1'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

C:\Users\user>cd basic1

C:\Users\user\basic1>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\user\basic1>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\user\basic1>git add README.md

C:\Users\user\basic1>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


C:\Users\user\basic1>git commit -m "로그인 개발"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'user@DESKTOP-HSBDQCC.(none)')

C:\Users\user\basic1>git config --global user.email "money683@naver.com"

C:\Users\user\basic1>git config --global user.name "Ilhwan123"

C:\Users\user\basic1>git commit -m "로그인 개발"
[main 5f3c6b8] 로그인 개발
 1 file changed, 3 insertions(+), 1 deletion(-)

C:\Users\user\basic1>git push
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 276 bytes | 276.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Ilhwan123/basic1.git
   57a9f0a..5f3c6b8  main -> main
