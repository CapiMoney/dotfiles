# Dotfiles

Dotfiles to get you up and running a whole lot faster. 🚀

## Table of Contents

* [Install](#install)
* [Usage](#usage)

## Install

Use `chezmoi` to initate a new machine.

```bash
$ sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply git@github.com:CapiMoney/dotfiles.git
```

See [chezmoi](https://chezmoi.io/) documentation for further instructions.

## Usage  

### Homebrew  

A minimal set of packages is managed by `dot_Brewfile.tmpl`. If you'd like to add packages specific to your system, you can create a file in your home directory called `.Brewfile.local`. These will then be managed and installed by chezmoi as well.  

### Git  

A minimal `.gitconfig` is templated by `dot_gitconfig.tmpl`. If you'd like to customise your Git configuration further, you can create a file in your home directory called `.gitconfig.local`, which will take precedence.  
