### Extract vim config

`$ git clone https://github.com/sswebcoder/vim_config.git ~/.config/vim/`

#### Add to end of yours .vimrc file

`source ~/.config/vim/main.conf`


### Set up Vundle

`$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.config/vim/bundle/Vundle.vim`

#### Launch vim and run 

`:PluginInstall`

#### Install YouCompleteMe plugin

`cd ~/.config/vim/bundle/YouCompleteMe`

`./install.py --clang-completer`
