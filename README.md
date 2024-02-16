# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

```zsh
$ sudo apt install git
```

### Stow

```zsh
$ sudo apt install stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```zsh
$ git clone git@github.com:nickyvanurk/dotfiles.git
$ cd dotfiles
```

Then use GNU stow to create symlinks

```zsh
$ stow .
```
