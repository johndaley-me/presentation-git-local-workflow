## Rebase Is Smart

It will magically remove merge commits when rebasing after the pull request was merged.

```bash
$ git merge --no-ff The-PR-branch
$ ...
$ git commit
$ ...
Pull request merged
$ git checkout mainline
$ git checkout my-feature
$ git rebase mainline
$ git log mainline...
Merge commit is gone
```
