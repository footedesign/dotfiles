# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
install coreutils
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, g-prefixed
install findutils
# Install Bash 4
install bash

# Install wget with IRI support
install wget --enable-iri

# Install more recent versions of some OS X tools
install vim --override-system-vi
tap homebrew/dupes
install homebrew/dupes/grep
tap josegonzalez/homebrew-php
install php55

# This formula didn’t work well last time I tried it:
#install homebrew/dupes/screen

# Install cask
brew tap phinze/homebrew-cask
brew install brew-cask

# Install other useful binaries
# More can be found at http://braumeister.org/ or by running $brew search
install ack
install bash-completion
install ffmpeg
install git
install graphicsmagick
install jpeg
install lynx
install node
install optipng
install pigz
install tree
install webkit2png
install zopfli

# Remove outdated versions from the cellar
cleanup
