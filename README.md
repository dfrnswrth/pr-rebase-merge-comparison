Rebase Method
=============

Pull Request Merge Method Comparison
------------------------------------

There was a merge conflict on `branch3__from_branch2` that could not be resolved
via the rebase method. Instead, I continued merging the other branches via
rebase, then squashed the conflicting merge (no conflicts with the squash
method).

```
$ log --graph --decorate --format=oneline --abbrev-commit --all
* fc17696 (HEAD -> master, origin/master, origin/HEAD) Branch3  from branch2 (#3)
* 1c559dc branch 5
* 79abe0b Revert "branch 4"
* ca48003 branch 4
* aacb5f0 branch 2
* 9d3e72f branch 1
* f23cea3 initial commit - create README.md
<Paste>
```
