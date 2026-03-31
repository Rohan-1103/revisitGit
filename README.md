## Practicing git commands
### Basic git commands
1. **git init**: Initialize a new local Git repository in current folder.
2. **git status**: Show current branch status, including staged/unstaged/untracked files.
3. **git add .**: Stage all changed files in the working directory for commit.
4. **git rm --cached**: Remove a file from staging (index) while keeping it in working tree.
5. **git branch**: List branches, or create one with `git branch <name>`.
6. **git commit -m**: Commit staged changes with a commit message.
7. **git branch -M**: Rename current branch (`-M` force rename even if target exists).
8. **git remote add origin** `link`: Add a remote repository URL as alias `origin`.
9. **git remote -v**: Show configured remotes and their fetch/push URLs.
10. **git push -u origin main**: Push local `main` to remote and set upstream tracking.
11. **git config --global user.name "Rohan-1103"**: Set global Git username for commits.
12. **git pull origin main**: Fetch and merge changes from remote `main` into local branch.

### Adding virtual conda environment
- **conda create -p venv python==3.13 -y**: Create a conda environment at path `venv` using Python 3.13.
- **conda activate venv/**: Activate the created conda environment for current shell.

### Branching strategies
13. **git branch branch_name**: Create a new branch with name `branch_name`.
14. **git checkout branch_name**: Switch working tree to `branch_name`.
15. **git merge branch_name**: Merge specified branch into current branch.
16. **git branch -d branch_name**: Delete local branch after merge (safe delete).

### Resolving and merging conflicts
17. **git log**: Show commit history and details of past commits.