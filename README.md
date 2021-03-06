# mac-dev-setup

FIRST - clean install `[sudo /Applications/Install\ OS\ X\ El\ Capitan.app/Contents/Resources/createinstallmedia --volume /Volumes/Untitled --applicationpath /Applications/Install\ OS\ X\ El\ Capitan.app --nointeraction]`

SECOND - start download of XCode

THIRD - explicity install command line tools `xcode-select --install`

FOURTH - install homebrew http://brew.sh

FOURTH-POINT-FIVE - install git `brew install git`
`git config --global user.name "Zach Heineman"`
`git config --global user.email "zach@heineman.info"`

FOURTH-POINT-FIVE(a) - clean up dock `brew install dockutil (https://github.com/kcrawford/dockutil)`
dock plist location = ~/Library/Preferences/com.apple.dock.plist

FIFTH - install homebrew cask `brew tap caskroom/cask`

`export HOMEBREW_CASK_OPTS="--appdir=/Applications"`

FOURTH-POINT-FIVE(b) - install github desktop `brew cask install github-desktop`

SIXTH - install Sublime Text 3 `brew cask install sublime-text`

SEVENTH - install Creative Cloud desktop https://www.adobe.com/creativecloud/desktop-app.html

EIGHTH - generate SSH key for Github https://help.github.com/articles/generating-ssh-keys/

NINTH - install Dropbox `brew cask install dropbox`

`sudo spctl --master-disable` #allows app downloads from "Anywhere"

`defaults write com.apple.finder AppleShowAllFiles -bool YES && killall Finder` #show dotfiles in finder

QUICK LOOK PLUGINS
brew cask install qlmarkdown

APPLICATIONS
brew cask install iterm2
brew cask install sublime-text

RUBY
brew install ruby-build
brew install rbenv
rbenv install 2.1.2
rbenv global 2.1.2
