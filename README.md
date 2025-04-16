# Solarized Dark Shell Prompt

This is a custom shell prompt based on the **Solarized Dark** color scheme. It is designed for use with iTerm2, though it can work with other terminal applications as well.

## Features

- **Git Status Indicators:** The prompt includes Git repository status indicators (e.g., `+`, `!`, `?`, `$`) to show the current state of your repository.
- **Dynamic Prompt:** Displays the username, hostname, and current directory, with special formatting when logged in as root or connected via SSH.
- **Custom Aliases:** The script sets up a series of useful Git, navigation, file listing, and system command aliases.
- **Solarized Color Scheme:** Uses Solarized Dark colors for various parts of the prompt.
- **Git Shortcuts:** Includes several convenient shortcuts for Git commands like `git status`, `git add .`, and `git commit -m`.
- **Terminal Title:** Sets the terminal title to the current working directory.

## Installation

1. Copy this script to your shell configuration file (e.g., `.bashrc`, `.zshrc`, etc.).
2. Ensure your terminal is configured to use **13pt Monaco** with **1.1 vertical spacing** for best results.

## Git Shortcuts

The following Git shortcuts are available:

- `gs` - `git status`
- `ga` - `git add .`
- `gc` - `git commit -m`
- `gp` - `git push`
- `gitlog` - `git log --graph --abbrev-commit --decorate --date=relative --all`

### Checkout & Branching

- `gco` - `git checkout`
- `gb` - `git branch`
- `gcb` - `git checkout -b`

### Stash & Diff

- `gd` - `git diff`
- `gst` - `git stash`
- `gpop` - `git stash pop`

### Navigation

- `..` - `cd ..`
- `...` - `cd ../..`
- `~` - `cd ~`

### List Files

- `l` - `ls -CF`
- `ll` - `ls -alF`

### System

- `c` - `clear`
- `reload` - `source ~/.bashrc`

### Custom Aliases Menu

- `show_alias` - Displays a list of all aliases with highlighted keys.

## Screenshot

A screenshot of the Solarized Dark theme in action:

![Solarized Dark Screenshot](http://i.imgur.com/EkEtphC.png)

## Credits

- Heavily inspired by [@necolas's dotfiles](https://github.com/necolas/dotfiles).
- Solarized color scheme taken from [http://git.io/solarized-colors](http://git.io/solarized-colors).
