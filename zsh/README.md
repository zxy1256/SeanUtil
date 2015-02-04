Types of shell
==============
 * Interactive login shell: 
    - Example: The first process when log in from SSH
    - Config loading order:
        + /etc/zshenv
        + ~/.zshenv
        + /etc/zprofile
        + ~/.zprofile
        + /etc/zshrc
        + ~/.zshrc
        + /etc/zlogin
        + ~/.zlogin
 * Interactive non-login shell: 
    - Example: Shell starts from Tmux
    - Config loading order:
        + /etc/zshenv
        + ~/.zshenv
        + /etc/zshrc
        + ~/.zshrc
 * Noninteractive non-login shell: 
    - Example: Script
    - Config loading order:
        + /etc/zshenv
        + ~/.zshenv

Referecnes
===========
 1. http://unix.stackexchange.com/questions/38175/difference-between-login-shell-and-non-login-shell
