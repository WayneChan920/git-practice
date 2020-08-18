# git-practice
practice the git command

* 6ceb5ba (HEAD) Using the command "git tag -d [TagName]" to remove the tag.
* e930cb7 Using the command "git show [TagName]" to show the tag information.
* f3d3831 (tag: v2.0.0) If you want to rollback, you can use the "git reflog" command to see the git command log list and do the "git reset --hard HEAD@{XX}" that what step you want to restore.
* a720f39 You must todo 2 steps with that "git commit --amend --allow-empty" to modify commit message and "git rebase --continue" to do the rebase-merge that if you want to keep the "empty commit" when you rebase and modify the commit message.
* e6b8634 You can append the "--keep-empty" parameter in the "git rebase -i XXXX" that makes the default of the "empty commit" will not mark to hide when you in the Rebase Vim dialog.
* 3bb83a4 (tag: v1.0.0) You can use the "git mv" or "mv + git add" command to rename the filename.
* e50998b You can also use the "-a" parameter to skip the "git add" step, and commit to Repository when the file already exists and modify. (It is not working if the file is new)
* acd6265 If you don't use the "-m" parameter when to commit, and it will show a vim dialog to ask you to enter some message.
* 4300905 You can commit an empty version by using the "--allow-empty" command.
* 635cbc6 init commit
