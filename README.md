# aliases
Handy aliases I have collected

## Importing aliases

To import any of the alias files to your local shell, you can either:

*(NOTE: you will need to start a new terminal session after completing either of these to use the newly imported aliases)*

- Copy individual aliases either from their Markdown or shell files to your local shell config (e.g. ~`~/.zshrc` for zsh)

- Import the entire collection of aliases automatically by running the following command (assuming you are using zsh):
`echo "\n" >> ~/.zshrc && cat aliases.sh >> ~/.zshrc`
  - Example: I want to import all of the git aliases into my zsh config:
    `echo "\n" >> ~/.zshrc && cat git/git-aliases.sh >> ~/.zshrc`

## Collections

![git logo](icons/git.png) [Git](git/Git.md)