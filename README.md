# Installation

Clone the repository:

    git clone git@github.com:branduren/emacs.git ~/dotfiles/emacs

Update submodules:

    cd ~/dotfiles/emacs
    git submodule init
    git submodule update submodule/


Build org-mode:

    cd ~/dotfiles/emacs/submodule/org-mode/
    make autoloads


Remember to set symlink:

    set symlink: ln -s ~/dotfiles/emacs/ ~/.emacs.d


# Packages

Currently installed with package manager:
* auctex
* magit
* yasnippet
* multi-web-mode
* php-mode
