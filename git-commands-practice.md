# Git Commands Practice

## 1. Check Repository Status

```bash
git status
```

Shows modified, staged, and untracked files in the working tree.

## 2. View Commit History

```bash
git log --oneline
```

Displays previous commits in a concise format.

## 3. Stage Changes

```bash
git add .
```

Stages changes for the next commit.

## 4. Commit Changes

```bash
git commit -m "Update Git command practice notes"
```

Records staged changes in the repository history.

## 5. Verify the Latest Commit

```bash
git log -1 --oneline
```

Displays the latest commit.

## Troubleshooting

**Issue:** `bash: log: command not found`

**Cause:** `log` was entered as a standalone shell command.

**Solution:** Run `git log --oneline` instead.
