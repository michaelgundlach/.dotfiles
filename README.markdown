# Dotfiles, Ho!

Custom configuration files.

# Setup

1. Clone this repo to ~/.dotfiles
2.  The following files (or whatever subset you like) should be symlinked from your home directory (taken from the output of `ls -lah | grep .dot` in my home directory)

```bash
.bash@ -> .dotfiles/bash
.bash_profile@ -> .dotfiles/bash/bash_profile
.gitignore@ -> .dotfiles/gitignore
.gvimrc@ -> .dotfiles/.gvimrc
.irbrc@ -> .dotfiles/irbrc
.vim@ -> .dotfiles/.vim
.vimrc@ -> .dotfiles/.vimrc
```

You can create these symlinks like, for example, `ln -s .dotfiles/.vimrc .vimrc`

(TODO: create a bash script to set up each of these with prompt, backing up your current one)
