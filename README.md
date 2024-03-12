Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
…
user@LAPTOP-QAG8EQOM MINGW64 /
$ cd /d

user@LAPTOP-QAG8EQOM MINGW64 /d
$ cd tugasWEB

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB
$ git clone
fatal: You must specify a repository to clone.

usage: git clone [<options>] [--] <repo> [<dir>]

    -v, --[no-]verbose    be more verbose
    -q, --[no-]quiet      be more quiet
    --[no-]progress       force progress reporting
    --[no-]reject-shallow don't clone shallow repository
    -n, --no-checkout     don't create a checkout
    --checkout            opposite of --no-checkout
    --[no-]bare           create a bare repository
    --[no-]mirror         create a mirror repository (implies bare)
    -l, --[no-]local      to clone from a local repository
    --no-hardlinks        don't use local hardlinks, always copy
    --hardlinks           opposite of --no-hardlinks
    -s, --[no-]shared     setup as shared repository
    --[no-]recurse-submodules[=<pathspec>]
                          initialize submodules in the clone
    --[no-]recursive ...  alias of --recurse-submodules
    -j, --[no-]jobs <n>   number of submodules cloned in parallel
    --[no-]template <template-directory>
                          directory from which templates will be used
    --[no-]reference <repo>
                          reference repository
    --[no-]reference-if-able <repo>
                          reference repository
    --[no-]dissociate     use --reference only while cloning
    -o, --[no-]origin <name>
                          use <name> instead of 'origin' to track upstream
    -b, --[no-]branch <branch>
                          checkout <branch> instead of the remote's HEAD
    -u, --[no-]upload-pack <path>
                          path to git-upload-pack on the remote
    --[no-]depth <depth>  create a shallow clone of that depth
    --[no-]shallow-since <time>
                          create a shallow clone since a specific time
    --[no-]shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --[no-]single-branch  clone only one branch, HEAD or --branch
    --no-tags             don't clone any tags, and make later fetches not to follow them
    --tags                opposite of --no-tags
    --[no-]shallow-submodules
                          any cloned submodules will be shallow
    --[no-]separate-git-dir <gitdir>
                          separate git dir from working tree
    --[no-]ref-format <format>
                          specify the reference format to use
    -c, --[no-]config <key=value>
                          set config inside the new repository
    --[no-]server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --[no-]filter <args>  object filtering
    --[no-]also-filter-submodules
                          apply partial clone filters to submodules
    --[no-]remote-submodules
                          any cloned submodules will use their remote-tracking branch
    --[no-]sparse         initialize sparse-checkout file to include only files at root
    --[no-]bundle-uri <uri>
                          a URI for downloading bundles before fetching from origin remote


user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB
$ git clone https://github.com/DiaMargareta/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB
$ cd belajarGIT

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git remote -v
origin  https://github.com/DiaMargareta/belajarGIT.git (fetch)
origin  https://github.com/DiaMargareta/belajarGIT.git (push)

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git branch
* main

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ touch Tugas-git

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ echo "GIT" > Tugas-git.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
warning: in the working copy of 'Tugas-git.txt', LF will be replaced by CRLF the next time Git touches it

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-git


user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan dan mengubah Tugas-git.txt"
[Tugas-git 65669e3] Menambahkan dan mengubah Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-git

nothing added to commit but untracked files present (use "git add" to track)

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan dan mengubah Tugas-git.txt"
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-git

nothing added to commit but untracked files present (use "git add" to track)

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git add Tugas-git

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan dan mengubah Tugas-git.txt"
[Tugas-git a557273] Menambahkan dan mengubah Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-git
Updating 38c00b0..a557273
Fast-forward
 Tugas-git     | 0
 Tugas-git.txt | 1 +
 2 files changed, 1 insertion(+)
 create mode 100644 Tugas-git
 create mode 100644 Tugas-git.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 537 bytes | 537.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/DiaMargareta/belajarGIT.git
   38c00b0..a557273  main -> main

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ echo "HTML" > Tugas-html.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
warning: in the working copy of 'Tugas-html.txt', LF will be replaced by CRLF the next time Git touches it

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-html.txt


user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan dan mengubah Tugas-html.txt"
[Tugas-html 9ca204f] Menambahkan dan mengubah Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-html
Updating a557273..9ca204f
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 301 bytes | 301.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/DiaMargareta/belajarGIT.git
   a557273..9ca204f  main -> main

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ echo "CSS" > Tugas-css.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
warning: in the working copy of 'Tugas-css.txt', LF will be replaced by CRLF the next time Git touches it

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-css.txt


user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan dan mengubah Tugas-css.txt"
[Tugas-css 755575f] Menambahkan dan mengubah Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
nothing to commit, working tree clean

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge tugas-css
Updating 9ca204f..755575f
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 294 bytes | 294.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/DiaMargareta/belajarGIT.git
   9ca204f..755575f  main -> main

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ echo "JS" >Tugas-js.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git add Tugas-js.txt
warning: in the working copy of 'Tugas-js.txt', LF will be replaced by CRLF the next time Git touches it

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-js.txt


user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan dan mengubah Tugas-js.txt"
[Tugas-js 4f482a2] Menambahkan dan mengubah Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge tugas-js
Updating 755575f..4f482a2
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 298 bytes | 298.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/DiaMargareta/belajarGIT.git
   755575f..4f482a2  main -> main

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ echo "MIDPROJECT" > Tugas-midProject

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject
warning: in the working copy of 'Tugas-midProject', LF will be replaced by CRLF the next time Git touches it

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-midProject.txt


user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject
        new file:   Tugas-midProject.txt


user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan dan mengubah Tugas-midProject"
[Tugas-midProject d0f5482] Menambahkan dan mengubah Tugas-midProject
 2 files changed, 1 insertion(+)
 create mode 100644 Tugas-midProject
 create mode 100644 Tugas-midProject.txt

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    Tugas-git
        deleted:    Tugas-midProject

no changes added to commit (use "git add" and/or "git commit -a")

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git restore Tugas-git

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git restore Tugas-midProject

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
nothing to commit, working tree clean

user@LAPTOP-QAG8EQOM MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
