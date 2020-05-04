# Git Errors

## The “fatal: refusing to merge unrelated histories” Git error

The “fatal: refusing to merge unrelated histories” Git error occurs when two unrelated projects are merged (i.e., projects that are not aware of each other’s existence and have mismatching commit histories).

Consider the following two cases that throw this error:
* You have cloned a project and, somehow, the .git directory got deleted or corrupted. This leads Git to be unaware of your local history and will, therefore, cause it to throw this error when you try to push to or pull from the remote repository.

* You have created a new repository, added a few commits to it, and now you are trying to pull from a remote repository that already has some commits of its own. Git will also throw the error in this case, since it has no idea how the two projects are related.

Solution
* The error is resolved by toggling the *allow-unrelated-histories* switch. After a **git pull** or **git merge** command, add the following tag: __git pull origin master --allow-unrelated-histories__

[Sorce-Website: https://www.educative.io/edpresso/the-fatal-refusing-to-merge-unrelated-histories-git-error](https://www.educative.io/edpresso/the-fatal-refusing-to-merge-unrelated-histories-git-error)

