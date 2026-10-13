# Git Hooks

Git [2.54](https://github.blog/open-source/git/highlights-from-git-2-54/) introduced config-based hooks, meaning no more 3rd party packages, symlinked, or copying.

## Support
- Python under uv or poetry
- lua
- terraform

## Usage

1. Pull this repo
2. chmod +x the pre-commit files
3. Copy .gitconfig to your ~/.gitconfig and fill in the paths to the pre-commit files
4. Enjoy!

If you want to disable the hooks for some reason, simply set the `SKIP_PRE_COMMIT` flag to 1 e.g.
```
SKIP_PRE_COMMIT=1 git commit -am "Yolo"
```