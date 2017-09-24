#!/usr/bin/env bash

#BREWFILE_IGNORE
if ! which brew >& /dev/null;then
  brew_installed=0
  echo Homebrew is not installed!
  echo Install now...
  echo ruby -e \"\$\(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install\)\"
  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  echo
fi
#BREWFILE_ENDIGNORE

# tap repositories and their packages

brew tap caskroom/cask
brew cask install 1password
brew cask install alfred
brew cask install appcleaner
brew cask install bartender
brew cask install calibre
brew cask install google-chrome
brew cask install java
brew cask install slack

brew tap homebrew/bundle

brew tap homebrew/core
brew install node
brew install pcre
brew install mas
brew install python
brew install tree
brew install openssl
brew install bash-completion
brew install icu4c
brew install xz
brew install sqlite
brew install zsh-completions
brew install python3
brew install openssl@1.1
brew install wget
brew install gdbm
brew install gradle
brew install zsh
brew install readline
brew install pkg-config

brew tap homebrew/python

brew tap homebrew/science

brew tap homebrew/versions

brew tap rcmdnk/file
brew install brew-file

# App Store applications
#appstore 682658836 GarageBand (10.2.0)
#appstore 408981434 iMovie (10.1.6)
#appstore 409183694 Keynote (7.3)
#appstore 409203825 Numbers (4.3)
#appstore 409201541 Pages (6.3)
#appstore 497799835 Xcode (9.0)
