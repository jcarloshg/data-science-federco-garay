# Git Log Commands - Most Used Examples

Here's a comprehensive list of the most commonly used `git log` commands with practical examples:

## 1. Basic Log Commands

### `git log`
Shows the commit history in reverse chronological order.
```bash
git log
```

### `git log --oneline`
Shows each commit on a single line with abbreviated commit hash.
```bash
git log --oneline
# Output: a1b2c3d Fix bug in data processing
```

### `git log -n <number>`
Limits the number of commits shown.
```bash
git log -5
# Shows only the last 5 commits
```

## 2. Formatting and Display Options

### `git log --graph`
Shows a text-based graphical representation of the commit history.
```bash
git log --graph --oneline
```

### `git log --pretty=format:"<format>"`
Customizes the output format.
```bash
git log --pretty=format:"%h - %an, %ar : %s"
# Output: a1b2c3d - John Doe, 2 hours ago : Fix data processing bug
```

### `git log --stat`
Shows files changed and number of lines added/removed.
```bash
git log --stat
```

## 3. Filtering Commands

### `git log --since` / `git log --until`
Shows commits within a specific time range.
```bash
git log --since="2 weeks ago"
git log --until="2023-12-31"
```

### `git log --author`
Shows commits by a specific author.
```bash
git log --author="John Doe"
```

### `git log --grep`
Searches commit messages for specific text.
```bash
git log --grep="bug fix"
```

### `git log -- <file>`
Shows commits that modified a specific file.
```bash
git log -- day-06/01-data-frames.ipynb
```

## 4. Advanced Filtering

### `git log -S <string>`
Shows commits that added or removed specific code (pickaxe search).
```bash
git log -S "pandas.DataFrame"
```

### `git log --follow <file>`
Shows the history of a file, including renames.
```bash
git log --follow utils.py
```

## 5. Branch and Merge History

### `git log <branch1>..<branch2>`
Shows commits in branch2 that are not in branch1.
```bash
git log main..feature-branch
```

### `git log --merge`
Shows commits involved in merge conflicts.
```bash
git log --merge
```

## 6. Most Useful Combinations

### `git log --oneline --graph --all`
Comprehensive view of all branches with visual representation.
```bash
git log --oneline --graph --all
```

### `git log --since="1 week ago" --author="John" --oneline`
Recent commits by specific author in compact format.
```bash
git log --since="1 week ago" --author="Jose" --oneline
```

### `git log --stat --summary`
Detailed view with file changes and summary.
```bash
git log --stat --summary
```

## 7. Quick Reference for Data Science Projects

For Jupyter notebook projects like this one, these commands are particularly useful:

```bash
# See changes to specific notebook
git log --oneline -- day-06/01-data-frames.ipynb

# Find commits related to data processing
git log --grep="data" --oneline

# See all changes in the last week
git log --since="1 week ago" --stat

# Visual representation of branch history
git log --graph --pretty=format:"%h <%an> %s" --abbrev-commit
```