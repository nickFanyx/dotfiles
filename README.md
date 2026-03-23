# My dotfiles

This directory contains the dotfiles for my system

# Requirements

Ensure you have the following installed on your system

### Git

```
pacman -S git

```

### Stow
for symlink

```
pacman -S stow

```

## Installation

First check out the dotfiles in your $HOME directory using git

```
$ git clone git@github.com/nickFanyx/dotfiles.git
$ cd dotfiles

```

then use GNU stow to create symlinks

```
$ stow .
```


