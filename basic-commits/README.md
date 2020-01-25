# README file for Git-Basic-Commits


2. What does `git log` look like?
`fatal: your current branch 'master' does not have any commits yet`


4. What does the output from `git status` look like now?
```
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	afile

nothing added to commit but untracked files present (use "git add" to track)
```

6. How does `git status` look now?
```
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   afile
```

8. How does `git status` look now?
```
On branch master
nothing to commit, working tree clean
```

10. What does `git status` look like now?
```
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   afile

no changes added to commit (use "git add" and/or "git commit -a")
```

12. What does `git status` look like now?
```
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   afile

```

15. What does the `status` look like now? The `log`?
Status:
```
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   afile

no changes added to commit (use "git add" and/or "git commit -a")
```

Git log:
```
commit 853ce918c593b0a3032615b83b5723e8527b401f
Author: Harrison Quarry <harrisonqleddy@gmail.com>
Date:   Fri Jan 24 18:44:45 2020 -0800

    Making commit after modifying

commit 7bca9f9f75a59d61aed6297346c3553ee6e7ca59
Author: Harrison Quarry <harrisonqleddy@gmail.com>
Date:   Fri Jan 24 18:42:15 2020 -0800

    created a file
```



