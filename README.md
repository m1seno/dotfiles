# My dotfiles
This directory contains the dotfiles for my system.

With this setup, it's easy to get the configurations I want for any new computer or virtual machine.

## Requirements
Ensure you have the following installed on your system.

### Git
```
sudo dnf install git
```

### Stow
```
sudo dnf install stow
```

## Installation
First, clone the repo into your $HOME directory using git
```
git clone git@github.com:m1seno/dotfiles.git
cd dotfiles
```

then use GNU stow to create symlinks.
```
stow .
```
