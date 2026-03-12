# gmail_gitops
my gmail filters but gitops

## Keeping actual filters in local branch that doesn't get synced
Setup
```bash
git switch -c local-filters
git config branch.local-filters.remote "DO-NOT-PUSH"
git config core.hooksPath .githooks
```
