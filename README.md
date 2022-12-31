# dotfiles

- to back up your `oh my zsh` stuff
- no need to backup the entire `.oh-my-zsh` folder, simply save the custom folder (symlink of course)
- to backup custom plugins, note the addresses of the git repos used

# symlinks
- https://stackoverflow.com/questions/8470315/git-commit-symlink-as-a-regular-file
- basically, use `ln` instead of `ls -s` to create a hard link, this is because if you use `ln -s`, it would create a symlink instead, and git would track that symlink