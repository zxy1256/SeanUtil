Setup a Development Machine
===========================

Setup File Structure
--------------------

    ~/
      Code/
        Web
        Android
        Utils
        Config


Install Softwares
-----------------

### Installation places

```
/usr/local/bin/
/usr/bin/
/usr/local/sbin
/usr/sbin
/usr/local/liba
/opt/local/bin
/Application
/Library
```

If `/usr/local` needs root permsion, then consider the following places:

```
/opt/local/bin
/opt/local/sbin
```
### Special steps for Mac

 * Install XCode (using AppStore)
 * Install MacPort
 * Install [slate](https://github.com/jigish/slate)

### Special steps for Linux

 * Install Xmonad

### Common steps

 * Install zsh
  - https://github.com/robbyrussell/oh-my-zsh/
  - http://site.douban.com/125980/widget/notes/4884065/note/232038698/

 * Install tmux

        ln -s <ABSOLUTE_PATH>/tmux/tmux.conf ~/.tmux.conf

 * Editor
    * [Config vim](./vim/README.md/#Config)
    * Install Sublime 3 Text
      * Install Package Control
      * Install emmet
    * Install Atom

 * Install MySQL
 * Install MongoDB

### NodeJS
 * Install NVM
   ``` 
    curl https://raw.github.com/creationix/nvm/v0.4.0/install.sh | sh
   ```
 * Install NodeJS
    ```
    nvm install v0.10
    ```      
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
