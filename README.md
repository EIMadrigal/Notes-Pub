# tmp

## Git

Normal pull:

```bash
git pull origin remote_branch:local_branch

```

local branch doesn't exist, but need to pull it from an existed remote branch:

```bash
git checkout -b local_branch origin/remote_branch
git checkout --track origin/remote_branch
```
