# generalist-cheat-cheet
Stuff that I won't remember but would like to remember

**Revert a range of commits**

`git revert OLDER_COMMIT^..NEWER_COMMIT`

**Cherry pick a range of commits**

`git cherry-pick OLDER_COMMIT..NEWER_COMMIT`

**Squash stuff**

`git rebase -i`

**Whitespace shit**

git merge -Xignore-all-space

Ignore whitespace when comparing lines.
This ignores differences even if one line has whitespace where the other line has none.

git merge -Xignore-space-change

Ignore changes in amount of whitespace.
This ignores whitespace at line end, and considers all other sequences of one or more whitespace characters to be equivalent.
