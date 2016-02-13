##  Interactive Rebase
### Pull Request Preparation

For local branches only (you haven't pushed)

```bash
$ git commit
$ git checkout mainline
$ git pull
$ git checkout some-feature
$ git rebase mainline
$ git rebase -i mainline
...
$ git log mainline...
```

note:
Your only chance in Git to fix typos
