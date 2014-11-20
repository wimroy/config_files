To checkout:
- git clone https://github.com/wimroy/config_files.git config_files
- cd config_files
- git submodule update --init


Vim:
Create a softlink to vim and vim/vimrc. Be sure to backup your original files before that, though.
- cd ~
- ln -s /path/to/vim    .vim
- ln -s /path/to/vim/vimrc    .vimrc


Tmux
- cd ~
- ln -s /path/to/tmux/tmux.conf    .tmux.conf



