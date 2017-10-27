# Abort Merge

For when you encounter merge conflicts and want to abort.

```
git reset --hard HEAD
```

- The `--hard` option discards all changes to the index and working tree since the specified commit (`HEAD` in this case)
- `HEAD` is a reference to the commit at the tip of your current branch
