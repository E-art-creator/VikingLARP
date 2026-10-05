
elham@ES MINGW64 /c/ES
$ git clone https://github.com/E-art-creator/VikingLARP.git
Cloning into 'VikingLARP'...
warning: You appear to have cloned an empty repository.

elham@ES MINGW64 /c/ES
$ ls
VikingLARP/

elham@ES MINGW64 /c/ES
$ cd VikingLARP

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        cloning af git repocitory.png

nothing added to commit but untracked files present (use "git add" to track)

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git add c
fatal: pathspec 'c' did not match any files

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git add cloning\ af\ git\ repocitory.png

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   cloning af git repocitory.png


elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git commit -m "screeshot af min git clone"
[main (root-commit) 76d2bde] screeshot af min git clone
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 cloning af git repocitory.png

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git diff origin/main
fatal: ambiguous argument 'origin/main': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git log
commit 76d2bde59a7cc7b2aee93efd28294a8b92420fb2 (HEAD -> main)
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 09:42:36 2026 +0200

    screeshot af min git clone

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git show ^C

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git show 76d2bde59a7cc7b2aee93efd28294a8b92420fb2
commit 76d2bde59a7cc7b2aee93efd28294a8b92420fb2 (HEAD -> main)
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 09:42:36 2026 +0200

    screeshot af min git clone

diff --git a/cloning af git repocitory.png b/cloning af git repocitory.png
new file mode 100644
index 0000000..daca6ac
Binary files /dev/null and b/cloning af git repocitory.png differ

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git push

Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 64.04 KiB | 16.01 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/E-art-creator/VikingLARP.git
 * [new branch]      main -> main




elham@ES MINGW64 /c/ES/VikingLARP (main)
$

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        VikingLARP-UseCases.md

nothing added to commit but untracked files present (use "git add" to track)

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config set advice.addEmptyPathspec false"

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git add .

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   VikingLARP-UseCases.md


elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git commit - m" VikingLARP-UseCases
> i markdown"
error: pathspec '-' did not match any file(s) known to git
error: pathspec 'm VikingLARP-UseCases
i markdown' did not match any file(s) known to git

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git commit -m" VikingLARP-UseCases
i markdown"
[main 1c8320b]  VikingLARP-UseCases i markdown
 1 file changed, 22 insertions(+)
 create mode 100644 VikingLARP-UseCases.md

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git log
commit 1c8320b2927f27e93ed13cd0114602488cb3bbf3 (HEAD -> main)
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 10:06:54 2026 +0200

     VikingLARP-UseCases
    i markdown

commit 76d2bde59a7cc7b2aee93efd28294a8b92420fb2 (origin/main)
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 09:42:36 2026 +0200

    screeshot af min git clone

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 667 bytes | 667.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/E-art-creator/VikingLARP.git
   76d2bde..1c8320b  main -> main

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git log
commit 1c8320b2927f27e93ed13cd0114602488cb3bbf3 (HEAD -> main, origin/main)
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 10:06:54 2026 +0200

     VikingLARP-UseCases
    i markdown

commit 76d2bde59a7cc7b2aee93efd28294a8b92420fb2
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 09:42:36 2026 +0200

    screeshot af min git clone

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   VikingLARP-UseCases.md

no changes added to commit (use "git add" and/or "git commit -a")

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git add VikingLARP-UseCases.md

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   VikingLARP-UseCases.md


elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git commit
[main e04c138] Opdatering af tabel
 1 file changed, 12 insertions(+), 10 deletions(-)

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git log
commit e04c1385b0fabeb35ca166998cd0e4e70d8b419b (HEAD -> main)
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 10:22:34 2026 +0200

    Opdatering af tabel

commit 1c8320b2927f27e93ed13cd0114602488cb3bbf3 (origin/main)
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 10:06:54 2026 +0200

     VikingLARP-UseCases
    i markdown

commit 76d2bde59a7cc7b2aee93efd28294a8b92420fb2
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 09:42:36 2026 +0200

    screeshot af min git clone

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 887 bytes | 887.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/E-art-creator/VikingLARP.git
   1c8320b..e04c138  main -> main

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   VikingLARP-UseCases.md

no changes added to commit (use "git add" and/or "git commit -a")

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config set advice.addEmptyPathspec false"

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git add VikingLARP-UseCases.md

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   VikingLARP-UseCases.md


elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git commit
[main 01aaea5] Retter "comment" med lille c til "Comment" med stort C
 1 file changed, 1 insertion(+), 1 deletion(-)

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git log
commit 01aaea54a1d21ebb91d044619bbfc824e6efde8c (HEAD -> main)
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 10:29:17 2026 +0200

    Retter "comment" med lille c til "Comment" med stort C

commit e04c1385b0fabeb35ca166998cd0e4e70d8b419b (origin/main)
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 10:22:34 2026 +0200

    Opdatering af tabel

commit 1c8320b2927f27e93ed13cd0114602488cb3bbf3
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 10:06:54 2026 +0200

     VikingLARP-UseCases
    i markdown

commit 76d2bde59a7cc7b2aee93efd28294a8b92420fb2
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 09:42:36 2026 +0200

    screeshot af min git clone

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 369 bytes | 369.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/E-art-creator/VikingLARP.git
   e04c138..01aaea5  main -> main

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   VikingLARP-UseCases.md

no changes added to commit (use "git add" and/or "git commit -a")

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config set advice.addEmptyPathspec false"

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git add VikingLARP-UseCases.md

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   VikingLARP-UseCases.md


elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git commit -m" tilføj Use Case 2 - Bestem salgsmoms"
[main 983204a]  tilføj Use Case 2 - Bestem salgsmoms
 1 file changed, 13 insertions(+), 1 deletion(-)

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git log
commit 983204a85b06e5de5bece3dd6c98e3b39a1f49be (HEAD -> main)
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 10:40:26 2026 +0200

     tilføj Use Case 2 - Bestem salgsmoms

commit 01aaea54a1d21ebb91d044619bbfc824e6efde8c (origin/main)
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 10:29:17 2026 +0200

    Retter "comment" med lille c til "Comment" med stort C

commit e04c1385b0fabeb35ca166998cd0e4e70d8b419b
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 10:22:34 2026 +0200

    Opdatering af tabel

commit 1c8320b2927f27e93ed13cd0114602488cb3bbf3
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 10:06:54 2026 +0200

     VikingLARP-UseCases
    i markdown

commit 76d2bde59a7cc7b2aee93efd28294a8b92420fb2
Author: Elham S. <elham-safari1@hotmail.com>
Date:   Mon Oct 5 09:42:36 2026 +0200

    screeshot af min git clone

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 410 bytes | 410.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/E-art-creator/VikingLARP.git
   01aaea5..983204a  main -> main

elham@ES MINGW64 /c/ES/VikingLARP (main)
$ ^C

elham@ES MINGW64 /c/ES/VikingLARP (main)
$
