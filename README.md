# dawson
zdawson@LIBLAB117 MINGW64 ~
$ cd dawson

zdawson@LIBLAB117 MINGW64 ~/dawson (master)
$ git clone https://github.com/alexisdawson/dawson.git
Cloning into 'dawson'...
warning: You appear to have cloned an empty repository.

zdawson@LIBLAB117 MINGW64 ~/dawson (master)
$ ls
dawson/  README.md

zdawson@LIBLAB117 MINGW64 ~/dawson (master)
$ cd dawson

zdawson@LIBLAB117 MINGW64 ~/dawson/dawson (master)
$ echo "cat" > pizza.txt

zdawson@LIBLAB117 MINGW64 ~/dawson/dawson (master)
$ ls
pizza.txt

zdawson@LIBLAB117 MINGW64 ~/dawson/dawson (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        pizza.txt

nothing added to commit but untracked files present (use "git add" to track)

zdawson@LIBLAB117 MINGW64 ~/dawson/dawson (master)
$ git add .
warning: LF will be replaced by CRLF in pizza.txt.
The file will have its original line endings in your working directory.

zdawson@LIBLAB117 MINGW64 ~/dawson/dawson (master)
$ git commit -m "cat"
[master (root-commit) f3cd6ed] cat
 Committer: Alexis Dawson <zdawson@uvic.ca>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 pizza.txt

zdawson@LIBLAB117 MINGW64 ~/dawson/dawson (master)
$ git push
Username for 'https://github.com': alexisdawson
CHCounting objects: 3, done.
Writing objects: 100% (3/3), 212 bytes | 212.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/alexisdawson/dawson.git
 * [new branch]      master -> master
