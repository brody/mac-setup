# Mac OS X setup

Facing the setup of a new machine (or the need to reinstall after a fresh OS install or the like), here's a very brief and basic list of the usual suspects, related to the setup of a mac computer to work with (mostly relate to a scripting languages context).

## Homebrew & Cask

The package manager is the default first thing I always install. Simply following the default steps. Homebrew downloads and installs the Command Line Tools for Xcode, so we're all good. Homebrew Cask is implemented as part of Homebrew now, so we're cask-enabled and ready from the start for our tapping. Finally, `brew-cask-upgrade` provides upgrade-like capabilities to cask, and we're all set.

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew tap buo/cask-upgrade
```

## Setup Mac App Store

If some previously purchased software from the Mac App Store needs to be included, we can use `mas` to ease the installs.

```bash
brew install mas
```

## My curated list of apps

Once we have `homebrew`, `cask` (and `mas` if needed) we're ready to go - (and yes, these lists might be scripted for some automation to install all, take this as just a curated set):

```bash
brew install 1password
brew install arc
brew install calibre
brew install cheatsheet
brew install cleanshot
brew install dash
brew install dropbox
brew install figma
brew install grammarly-desktop
brew install hiddenbar
brew install iconjar
brew install iina
brew install imageoptim
brew install karabiner-elements
brew install kindle
brew install linear-linear
brew install miro
brew install notion
brew install pocket-casts
brew install raycast
brew install rectangle
brew install rightfont
brew install rocket
brew install slack
brew install spotify
brew install visual-studio-code
brew install warp
brew install zoom
```

### Mac App Store

```bash
# Amphetamine
mas install 937984704
# Bear
mas install 1091189122
# DayOne
mas install 1055511498
# Endel
mas install 1346247457
# Everyday
mas install 1394150432
# Fantastical
mas install 975937182
# Infuse
mas install 1136220934
# Keka
mas install 470158793
# Paste
mas install 967805235
# Pixave
mas install 924891282
# NordVPN
mas install 905953485
# Omnivore
mas install 1564031042
# Spark Classic
mas install 1176895641
# Things
mas intall 904280696
# WhatsApp
mas install 310633997
# World Clock Pro
mas install 858446756
# Zight (prev CloudApp)
mas install 937984704
```
