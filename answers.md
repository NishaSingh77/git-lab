answer 1 =
git version 2.26.2.windows.1

answer 2 =
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
credential.helper=manager
user.name=Nisha Singh
user.email=ns525219@ohio.edu
(END)

answer 3 =
git add --help command opens a new manual page
git --help gives the following output describing basic working and operations of it.
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout

examine the history and state (see also: git help revisions)
   bisect            Use binary search to find the commit that introduced a bug
   diff              Show changes between commits, commit and working tree, etc
   grep              Print lines matching a pattern
   log               Show commit logs
   show              Show various types of objects
   status            Show the working tree status

grow, mark and tweak your common history
   branch            List, create, or delete branches
   commit            Record changes to the repository
   merge             Join two or more development histories together
   rebase            Reapply commits on top of another base tip
   reset             Reset current HEAD to the specified state
   switch            Switch branches
   tag               Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch             Download objects and refs from another repository
   pull              Fetch from and integrate with another repository or a local branch
   push              Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

answer 4 =
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

answer 5 =
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

answer 6 =
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

answer 7 =
On branch master
nothing to commit, working tree clean

answer 8 =
commit d5299201a9b5f978f2fa014a1802344b03fa2a10 (HEAD -> master)
Author: Nisha Singh <ns525219@ohio.edu>
Date:   Fri May 15 16:25:37 2020 -0400

    Initial commit

answer 9 =
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

answer 10 = 
No! The changes did not appear

answer 11 = 
We get a rejected message
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 396 bytes | 396.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/NishaSingh77/git-lab.git
   d529920..db76f15  master -> master
PS C:\Users\nisha\Desktop\cs2400\git-lab> git push
fatal: unable to access 'https://github.com/NishaSingh77/git-lab.git/': The requested URL returned error: 504

answer 12 =
Yes! They appeared in the README.md file

answer 13 = 
    Directory: C:\Users\nisha\Desktop\cs2400\git-lab-2


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----        5/15/2020   4:42 PM            302 .gitignore
-a----        5/15/2020   4:42 PM             11 README.md

