This project contains standard setup. To use...

    cd $HOME
    git clone https://github.com/d-smith/son-of-dotfiles
    ln -sb son-of-dotfiles/.vimrc .
    mv .bashrc .bashrc.bak
    ln -sb son-of-dotfiles/.bashrc .
    ./son-of-dotfiles/set-proxy.sh

If you use git you should also update the .bashrc to set your git
user name and user email - see the commented out example lines 
in .bashrc.
