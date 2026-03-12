# gmail_gitops
my gmail filters but gitops

We'll be mostly using [gmailctl](https://github.com/mbrt/gmailctl) for filter generation

### Setup
Keeping actual filters in local branch that does not get synced
```bash
git config core.hooksPath .githooks
git worktree add -b local-filters local-filters
cd local-filters
git config branch.local-filters.remote "DO-NOT-PUSH"
git rm -r ./*
git commit -a -m "Cleanup to init"
cd -
```

### Usage
store filters in the folder `local-filters`
