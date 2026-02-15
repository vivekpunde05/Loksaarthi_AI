# Daily Git Workflow Guide

This guide will help you commit and push your daily work to GitHub.

## Quick Daily Workflow

### 1. Check what files have changed
```bash
git status
```

### 2. Add your changes
```bash
# Add all changes
git add .

# Or add specific files
git add filename.js
git add folder/
```

### 3. Commit your changes
```bash
git commit -m "Brief description of what you did"
```

### 4. Push to GitHub
```bash
git push origin master
```

## Common Commit Message Examples

```bash
# Feature work
git commit -m "Add user authentication service"
git commit -m "Implement recommendation engine"

# Bug fixes
git commit -m "Fix language detection issue"
git commit -m "Resolve database connection error"

# Updates
git commit -m "Update README with setup instructions"
git commit -m "Refactor AI assistant service"

# Tests
git commit -m "Add unit tests for profile analyzer"
git commit -m "Add property tests for eligibility matching"
```

## Daily Workflow Commands

### Start your day
```bash
# Get latest changes from GitHub
git pull origin master
```

### During the day
```bash
# Check what you've changed
git status

# See detailed changes
git diff

# Add and commit frequently
git add .
git commit -m "Your message here"
```

### End of day
```bash
# Push all your commits to GitHub
git push origin master
```

## Useful Git Commands

### View commit history
```bash
git log --oneline
git log --oneline -5  # Last 5 commits
```

### Undo changes (before commit)
```bash
# Discard changes in a file
git checkout -- filename.js

# Unstage a file
git reset HEAD filename.js
```

### View what changed in last commit
```bash
git show
```

### Create a new branch for a feature
```bash
git checkout -b feature-name
git push origin feature-name
```

## Best Practices

1. **Commit often**: Make small, focused commits
2. **Write clear messages**: Describe what and why, not how
3. **Pull before push**: Always get latest changes first
4. **Test before commit**: Make sure your code works
5. **Push daily**: Don't let commits pile up locally

## Troubleshooting

### If push is rejected
```bash
# Pull latest changes first
git pull origin master

# Then push again
git push origin master
```

### If you have merge conflicts
```bash
# Open the conflicted files and resolve manually
# Then:
git add .
git commit -m "Resolve merge conflicts"
git push origin master
```

### If you need to undo last commit
```bash
# Keep changes but undo commit
git reset --soft HEAD~1

# Discard changes and undo commit
git reset --hard HEAD~1
```

## Quick Reference Card

| Command | What it does |
|---------|-------------|
| `git status` | Show changed files |
| `git add .` | Stage all changes |
| `git commit -m "msg"` | Commit with message |
| `git push origin master` | Push to GitHub |
| `git pull origin master` | Get latest from GitHub |
| `git log --oneline` | View commit history |
| `git diff` | See what changed |

## Need Help?

- Check status: `git status`
- View help: `git help`
- View command help: `git help commit`