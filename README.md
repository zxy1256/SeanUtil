Setup a Development Machine
========

Setup File Structure
------

    ~/
      Code/
        Web
        Android
        Utils
        Config


Install Softwares
-----

## Tools
 * Install XCode (Mac only, using AppStore)

 * [Install XCode command line tool](http://railsapps.github.io/xcode-command-line-tools.html)

 * Install Homebrew (Mac only)
  - [Fix problems with Yosemite](http://jcvangent.com/fixing-homebrew-os-x-10-10-yosemite/)

 * Install git

 * Install zsh
  - https://github.com/robbyrussell/oh-my-zsh/
  - http://site.douban.com/125980/widget/notes/4884065/note/232038698/

 * Install tmux

        brew install tmux
        ln -s <ABSOLUTE_PATH>/tmux/tmux.conf ~/.tmux.conf

 * Config vim
  - Install pathogen.vim
  - Install l9
  - Install NERDTree
  - Install FuzzyFinder
  - Update vimrc

            ln -s <ABSOLUTE_PATH>/vim/vimrc ~/.vimrc

 * Install Sublime 3 Text
  * Install Package Control
  * Install emmet

 * Install MySQL
 * Install MongoDB

### NodeJS
 * Install NVM
    
    curl https://raw.github.com/creationix/nvm/v0.4.0/install.sh | sh

 * Install NodeJS
      
    nvm install v0.10
      
 * Install the following global nodepackages
  - Bower
  - Grunt
  - Gulp
  - Karma
  - Jasmine

### Python
  - pandas
  - matplotlit

### Ruby


### Go

### Media Related
 * Install ffmpeg