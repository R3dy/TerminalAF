# TerminalAF
An unecessarily bright and intoxicatingly rad super dope setup for looking extra cool while you're doing terminal stuff on Zoom in front of other people ;)

![](./screenshots/terminalaf.png)

# Dependencies (because I can't spell prerequesitsises...?)
In order to make your terminal look cooler than everybody elses, you're gonna need the following:

* [Alacritty](https://alacritty.org/) because stock terminals are for babies
* Some [Alacritty themes](https://github.com/alacritty/alacritty-theme), I'm using tokyo-night
* [Oh My ZSH](https://ohmyz.sh/) because lots of smart people use it and you'll feel smarter if you use it
* Tmux because I said so
*  The Tmux Plugin Manager or [tpm](https://github.com/tmux-plugins/tpm) for short
* [NvChad](https://nvchad.com/), or whatever Neovim setup you prefer
* A [Nerd Font](https://www.nerdfonts.com/font-downloads), I use SauceCodePro

You're also gonna need about 15 minutes to follow the preceeding setup guide because I'm just not cool enough to make a one-liner :(

# OSX setup
The image above was taken on a Mac, you should be able to produce something near identical using these instructions.

## Alacritty
1. Install Alacritty using the macOS binary from https://alacritty.org
2. Create the `~/.config/alacritty/` directory if it doesn't already exist
3. Follow [the instructions](https://github.com/alacritty/alacritty-theme) from the alacritty-theme git repo to create the `~/.config/alacritty/themes` directory and then clone the repo there
4. Finally, copy the `alacritty.yml` file from this repo to your `~/.config/alacritty/` directory


## OhMyZsh
1. Check out the one-liner from the Oh My ZSH [install](https://ohmyz.sh/#install) page.
2. Add the following somewhere in your `~/.zshrc`

```bash
export TERM="xterm-256color"
export PATH="$PATH:~/.config/nvim/bin"
export PATH="$PATH:$HOME/.tmux/plugins/tpm"
export PATH="$PATH:~/.config/nvim/bin"
alias vim="/opt/homebrew/bin/nvim"

alias nano="/opt/homebrew/bin/nvim"
# lol jk ;-) 
```

## Tmux

## Neovim with NvChad

## Nerd Font
