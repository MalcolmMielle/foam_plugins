# Git Pull

## Solve Git Pull Warning

The short version is that if you're on the main branch use `git config pull.rebase true` to do rebase.
Otherwise, do `git config pull.ff only` to only fast-forward without merge commits.
[See this answer](https://stackoverflow.com/a/62653400/2651229)

Omit `--global` and `--system` flag to [only set the config in the current repo](https://stackoverflow.com/a/18181510/2651229).