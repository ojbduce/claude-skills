# Sync Skills to GitHub

Commit and push any changes in ~/.claude/skills to the ojbduce/claude-skills GitHub repo.

## Steps

1. Run the following bash commands in sequence:
   ```bash
   cd ~/.claude/skills && git add -A && git status
   ```
2. If there are changes to commit, run:
   ```bash
   cd ~/.claude/skills && git commit -m "Update skills" && git push
   ```
3. Report back with what was committed and pushed, or confirm already up to date.
