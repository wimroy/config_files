To checkout:
- git clone https://github.com/wimroy/vim_profile.git    vim
- cd vim
- git submodule update --init


Create a softlink to vim and vim/vimrc. Be sure to backup your original files before that, though.
- cd ~
- ln -s /path/to/vim    .vim
- ln -s /path/to/vim/vimrc    .vimrc


The following bundles are currently installed:
- pathogen
- python-mode
- syntastic
- nerdtree
- vim-airline
- vim-colors-solarized
