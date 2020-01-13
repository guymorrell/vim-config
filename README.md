Install like this:

    cd ~/
    brew install cmake macvim
    git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
    cp ./vimrc ~/.vim/vimrc
    ln -s ~/.vim/vimrc ~/.vimrc 
    cd ~/.vim/bundle/YouCompleteMe
    ./install.py
    vim +PluginInstall +qall
