## Tip

Delete "old" branches so that "git branch" gives you a short list of active
branches.

```bash
$ git branch -vv
...
$ git branch
...
$ git branch -d old-branch
```

note:
Old doesn't mean dead. Just that you're not actively working on it.
