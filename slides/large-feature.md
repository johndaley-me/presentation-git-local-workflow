## Scenario 2
### Large Feature
(1-2 days)

```bash
$ git checkout mainline
$ git pull
$ git checkout -b dependent-feature
$ git merge --no-ff The-PR-branch-I-depend-on
...
```

note:
It's the same as the previous slide.
