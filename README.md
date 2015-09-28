# mac-dev-setup

FIRST - clean install
SECOND - start download of XCode

sudo spctl --master-disable #allows app downloads from "Anywhere"
defaults write com.apple.finder AppleShowAllFiles -bool YES #show dotfiles in finder

COMMAND LINE TOOLS
xcode-select --install

QUICK LOOK PLUGINS
brew cask install qlmarkdown

APPLICATIONS
brew cask install iterm2

brew tap caskroom/versions
brew cask install sublime-text3

RUBY
brew install ruby-build
brew install rbenv
rbenv install 2.1.2
rbenv global 2.1.2
