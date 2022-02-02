## Git

### gfix
Amend commit (e.g. `gfix fc54ac3` will create a fixup for the commit fc54ac3)
```bash
alias gfix="git commit --fixup"
```

### gash
Auto-squash fixes (e.g. `gash master` will rebase the current branch on master and autosquash all the fixups made with gfix)
```bash
alias gash="git rebase --autosquash --interactive"
```

### gst
Show status of current branch
```bash
alias gash="git status"
```
