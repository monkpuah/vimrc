Jack's Vim config
==================

Customized from [Maple's Vim Config](https://github.com/humiaozuzu/dot-vimrc)

## Installation

1. Backup your old vim configuration files:

        mv ~/.vim ~/.vim.orig
        mv ~/.vimrc ~/.vimrc.orig

2. Clone and install this repo:

        git clone https://github.com/jagandecapri/vimrc.git ~/.vim
        ln -s ~/.vim/.vimrc ~/.vimrc

3. Setup `Vundle`:

        git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle

4. Install bundles. Launch vim (ignore the errors and they will disappear after installing needed plugins) and run:

        :BundleInstall
