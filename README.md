# My dotfiles

This directory contains dotfiles for my Linux systems

## Requirements

Ensure that the following are installed

### Git

```
pacman -S git
```

### Stow

```
pacman -S stow
```

## Installation

Check out the dotfiles repo in $HOME directory using git

```
$ git clone git@github.com/gstoltman/dotfiles.git
$ cd dotfiles
```

Then use Stow to create symlinks

```
stow .
```
