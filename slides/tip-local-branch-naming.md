## Tip

Prefix local branches with "wip" until you are ready to push.
This way it's very unlikely you'll ever accidentally use rebase to rewrite remote history.

```bash
$ git branch -m wip-234-my-feature feature/JIRA-KEY-234-my-feature
```
