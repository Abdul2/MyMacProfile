
More of reminder for me but it mayabe helpful to others.

```
  
# brew
    
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  
$ brew update

# git
  
$ brew install git

# lastpass
    
$ brew cask install lastpass
$ cd  /usr/local/Caskroom/lastpass/latest/
$ Open LastPass\ Installer.app/ # manual
    

# sublime 
   
$ brew cask install sublime-text
   
#dropbox
 
$ brew cask install --appdir="/Applications" dropbox 
  
# vim
 
$ brew install vim --with-luajit 

#slack

$ brew cask install slack

# quick silver

$ brew cask install --appdir="/Applications" quicksilver

#wget

$ brew install wget

#markdown
brew cask install mou

#oh myzh
brew install zsh
sudo -s 'echo /usr/local/bin/zsh >> /etc/shells' && chsh -s /usr/local/bin/zsh

#other

other=(node tree unrar watch wget curl)
brew install ${[other@]}
brew cleanup

#other apps
other=(vagrant docker virtualbox xquartz inkscape)
brew install ${[other@]}
brew cleanup

```


