Powerline for [Prezto](http://github.com/sorin-ionescu/prezto) ZSH


## Features

* Single line prompt
* Git branch info (current branch and modified states)
* Time since last commit
* Current ruby version via ruby-info

![Example](https://raw.github.com/davidjrice/prezto_powerline/master/prompt.png)

## Dependencies

* [skwp/dotfiles](http://github.com/skwp/dotfiles) *(YADR)*
* [prezto](https://github.com/sorin-ionescu/prezto) (included by YADR)

## Installation

    # Install YADR
    git clone https://github.com/skwp/dotfiles ~/.yadr
    cd ~/.yadr && rake install

    # Create a ~/.secrets file (required by YADR)
    touch ~/.secrets

    # Install the prompt
    curl https://raw.github.com/sebastianpicklum/prezto_shpowerline/master/prompt_powerline_setup > ~/.zsh.prompts/prompt_powerline_setup

    # Install Solarized
    git clone https://github.com/altercation/solarized
    cd solarized
  
    # e.g. for iTerm
    cd iterm2-colors-solarized/
    open Solarized\ Dark.itermcolors
    # this should load the colours for iTerm, but they are not configured yet

    # in iTerm2 open preferences 
    #   profiles > default > colours > load presets > Solarized Dark
    #   profiles > default > terminal > report terminal type > "xterm-256color"

    # Enable
    echo "prompt shpowerline" > ~/.zsh.after/prompt.zsh


## Inspiration

Based on the great
* [prezto_powerline](https://github.com/davidjrice/prezto_powerline)

which was inspired by:

* [oh-my-zsh-powerline-theme](http://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme)
* [robbl oh-my-zsh theme](http://github.com/robbl/oh-my-zsh-config)
* [SKWP prezto theme](http://github.com/skwp/dotfiles/blob/master/zsh/prezto-themes/prompt_skwp_setup)

## TODO

* Powerline font support
* nvm version info support
* color optimization
* increase configurability
* more intelligent functions
