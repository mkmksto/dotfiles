# dotfiles

- to back up your `oh my zsh` stuff
- no need to backup the entire `.oh-my-zsh` folder, simply save the custom folder (symlink of course)
- to backup custom plugins, note the addresses of the git repos used

# Installation on another machine (not yet tested)

- Install `zsh`, then set as default shell (pick the option where it creates a config file but doesn't populate it) (use the chmod command thing i guess)
- Install `oh my zsh`, do not configure
- clone your gh repo into the particular folder (`git clone <repo> <folder>`)
- run `sh install/.sh`
- run `sh install-oh-my-plugins.sh` (not yet working, rewrite this)
