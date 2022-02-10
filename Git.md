## Git

### gst
Show status of current branch
```bash
alias gst="git status"
```

### gcmsg
Create a commit with a message
```bash
alias gcmsg="git commit --message"
```

### gcb
Create a new branch
```bash
alias gcb="git checkout -b"
```

### gco
Checkout a branch
```bash
alias gco="git checkout"
```

### gapa
Stage changes in patch mode. Allows for selecting changes to stage by hunk.
```bash
alias gapa="git add --patch"
```

### gcp
Cherry-pick a commit
```bash
alias gcp="git cherry-pick"
```

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
