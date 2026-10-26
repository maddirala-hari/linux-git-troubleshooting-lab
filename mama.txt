# Git Troubleshooting Record

## Issue
The terminal displayed this error:

`bash: log: command not found`

## Cause
The `log` command was entered directly in the terminal instead of using the Git command.

## Solution
Run the correct command:

```bash
git log --oneline
```

## Verification
Check whether the recent Git commits are displayed in the terminal.

```bash
git status
git log -1 --oneline
```

## Learning
Git commands must be executed with the correct Git subcommand syntax. Always check the command and repository status when troubleshooting.
