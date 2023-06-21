Instruction 


Creating a new directory for github

(base) C:\Users\shede>cd codelouisville

(base) C:\Users\shede\codelouisville>git init
Initialized empty Git repository in C:/Users/shede/codelouisville/.git/

(base) C:\Users\shede\codelouisville>git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

(base) C:\Users\shede\codelouisville>git branch -m main

(base) C:\Users\shede\codelouisville>git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)

(base) C:\Users\shede\codelouisville>git config --global init.defaultBranch main

(base) C:\Users\shede\codelouisville>code .

(base) C:\Users\shede\codelouisville>git remote add origin https://github.com/NieshaThomas/codelouisville.git

(base) C:\Users\shede\codelouisville>git add .

(base) C:\Users\shede\codelouisville>git commit -a -m 'initial commit'
fatal: paths 'commit' ...' with -a does not make sense

(base) C:\Users\shede\codelouisville>git commit -a -m "initial commit"
[main (root-commit) 73ea8fd] initial commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

(base) C:\Users\shede\codelouisville>git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


(base) C:\Users\shede\codelouisville>git push --set-upstream origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 218 bytes | 109.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/NieshaThomas/codelouisville.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

(base) C:\Users\shede\codelouisville>git add .
warning: in the working copy of 'data_2_checks.ipynb', LF will be replaced by CRLF the next time Git touches it

(base) C:\Users\shede\codelouisville>git commit -a -m "add data_2_checks"
[main bfe8ab9] add data_2_checks
 1 file changed, 1247 insertions(+)
 create mode 100644 data_2_checks.ipynb

(base) C:\Users\shede\codelouisville>git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.66 KiB | 1.33 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/NieshaThomas/codelouisville.git
   73ea8fd..bfe8ab9  main -> main

(base) C:\Users\shede\codelouisville>





Demo
	Go to github create new respiratory
Return to powershell(anaconda)
Hit the add new prompt
	Git clone( this is the link to the repo on   github)
	Cd (name of repo)
	Code .






