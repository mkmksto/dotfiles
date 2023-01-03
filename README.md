# dotfiles

- to back up your `oh my zsh` stuff
- no need to backup the entire `.oh-my-zsh` folder, simply save the custom folder (symlink of course)
- to backup custom plugins, note the addresses of the git repos used

# symlinks

- https://stackoverflow.com/questions/8470315/git-commit-symlink-as-a-regular-file
- basically, use `ln` instead of `ls -s` to create a hard link, this is because if you use `ln -s`, it would create a symlink instead, and git would track that symlink
- don't do above, just to `ln -s` from the dotfiles folder

# Installation on another machine (not yet tested)

- Install `zsh`, then set as default shell (pick the option where it creates a config file but doesn't populate it)
- Install `oh my zsh`
- clone your gh repo into the particular folder (`git clone <repo> <folder>`)
- run `sh install/.sh`
- run `sh install-oh-my-plugins.sh` (not yet working, rewrite this)
