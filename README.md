# gmail_gitops
my gmail filters but gitops

We'll be mostly using [gmailctl](https://github.com/mbrt/gmailctl) for filter generation

### Setup
Keeping actual filters in local branch that does not get synced
```bash
git worktree add -b local-filters local-filters
git config branch.local-filters.remote "DO-NOT-PUSH"
git config core.hooksPath .githooks
```

### Usage
store filters in the folder `local-filters`
