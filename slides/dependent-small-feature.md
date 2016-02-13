## Scenario 2
### Dependent Small Feature

```bash
$ git checkout mainline
$ git pull
$ git checkout -b dependent-feature
$ git merge --no-ff The-PR-branch-I-depend-on
...
```

note:
Always pull to be up-to-date
I recommend the --no-ff so that you can use revert for the entire merge later or so if you do local rebasing it
will be easier to see where you are.
By always branching off of mainline we can more easily
keep a mental map of where we are which is great for context
switching.
