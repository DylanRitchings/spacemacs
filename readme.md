## Installation
```bash
windows="/c/Users/dylan.ritchings/AppData/Roaming"
mac="$HOME"

git --git-dir="$HOME/.spacemacs" --work-tree="$HOME" init
export GIT_DIR="$HOME/.spacemacs"

cd $HOME/.dotfiles/shared
git config status.showUntrackedFiles no

git remote add origin https://github.com/DylanRitchings/shared-dotfiles.git
git fetch

# WARNING: Overwrites files
git reset --hard origin/main
```
