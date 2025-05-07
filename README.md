[![wakatime](https://wakatime.com/badge/github/thederpykrafter/cryptic.zsh-theme.svg)](https://wakatime.com/badge/github/thederpykrafter/cryptic.zsh-theme)
# cryptic.zsh-theme

I used [aphrodite-terminal-theme](https://github.com/win0err/aphrodite-terminal-theme) as a starting point for this theme.

The one charachter gap on the right side is to make resized windows look cleaner. However it still may not update properly with some environments.

# Preview

Linux

<img src="https://github.com/thederpykrafter/cryptic.zsh-theme/blob/main/screenshots/desktop-screenshot.png" alt="" width="600"/>

Termux

> Tux(Penguin) is not part of this theme. It is part of my [zsh config](https://github.com/thederpykrafter/zsh)

<img src="https://github.com/thederpykrafter/cryptic.zsh-theme/blob/main/screenshots/termux-screenshot.jpg" alt="" height="600"/>

# Installation

Remove themes dir if it exists

```zsh
cd $ZSH_CUSTOM
rm -rf $ZSH_CUSTOM"themes"
git add . && git commit -m "cryptic theme prep"
```

Clone repo
```zsh
git clone https://github.com/thederpykrafter/cryptic.zsh-theme.git $ZSH_CUSTOM"themes/"
```
> OR

Add submodule

```zsh
git submodule add https://github.com/thederpykrafter/cryptic.zsh-theme themes
git commit -m "cryptic theme setup"
```

Fix push (`this is here for later me`)

```zsh
git remote set-url origin git@github.com:thederpykrafter/cryptic.zsh-theme
```

