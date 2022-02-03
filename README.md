# dotfiles

Install nvm to manage node versions

Install Homebrew using shell script recommended on their website
Install NVM using their shell script
Install Node.js using NVM and Homebrew
Install Yarn using Homebrew

```shell
nvm install lts/fermium # substitute with the latest LTS release
brew install node
brew install yarn
```

## ZSH stuff

```
brew install zsh-autosuggestions
brew install zsh-history-substring-search
brew install zsh-syntax-highlighting
brew install zsh-completions

yarn global add pure-prompt
```

## GitHub CLI

```
brew install gh
```

## Java Development Kit

```
brew install --cask adoptopenjdk/openjdk/adoptopenjdk8
```

## Ruby stuff - usually for iOS dev tools

Install rbenv using brew
Install a dedicated version of Ruby
Install Bundler using RubyGems - for global set up, stop here
Install CocoaPods and Fastlane using Bundler - project specific

```
brew install rbenv
rbenv install 2.7.4
gem install bundler
bundle install cocoapods
bundle install fastlane
bundle exec pod install
```

## React Native stuff

Optional

```
brew install watchman
```
