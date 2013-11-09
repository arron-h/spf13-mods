spf13-mods
==========

My own mods to spf13's great vim bundle. Removed some unneeded features, and changed the completion engine.

Installation
============

Just drop these files at ~/.
Some things you'll need to do once you've done that:
* Download and install a Powerline-patched font from: <https://github.com/Lokaltog/powerline-fonts>
  * I like Source Code Pro, and it needs to be converted from otf to ttf before it's installed.
    * On Ubuntu I had to add: set guifont=Source\ Code\ Pro\ for\ Powerline\ 10 to ~/.gvimrc for gvim to pick it up.
* Run :BundleClean! and :BundleInstall to add/remove the new bundles.
* Compile YCM
  * Navigate to ~/.vim/bundles/YouCompleteMe/
  * run ./install.sh --clang-completer

Plugins
=======

Here's a list of plugins that are installed after these scripts are loaded:

* Bundle 'gmarik/vundle'
* Bundle 'MarcWeber/vim-addon-mw-utils'
* Bundle 'tomtom/tlib_vim'
* Bundle 'scrooloose/syntastic'
* Bundle 'scrooloose/nerdcommenter'
* Bundle 'godlygeek/tabular'
* Bundle 'octol/vim-cpp-enhanced-highlight'
* Bundle 'Valloric/YouCompleteMe'
* Bundle 'SirVer/ultisnips'
* Bundle 'majutsushi/tagbar'
* Bundle 'scrooloose/nerdtree'
* Bundle 'altercation/vim-colors-solarized'
* Bundle 'spf13/vim-colors'
* Bundle 'tpope/vim-surround'
* Bundle 'spf13/vim-autoclose'
* Bundle 'kien/ctrlp.vim'
* Bundle 'terryma/vim-multiple-cursors'
* Bundle 'vim-scripts/sessionman.vim'
* Bundle 'matchit.zip'
* Bundle 'bling/vim-airline'
* Bundle 'Lokaltog/vim-easymotion'
* Bundle 'godlygeek/csapprox'
* Bundle 'jistr/vim-nerdtree-tabs'
* Bundle 'flazz/vim-colorschemes'
* Bundle 'mbbill/undotree'
* Bundle 'myusuf3/numbers.vim'
* Bundle 'nathanaelkane/vim-indent-guides'
* Bundle 'vim-scripts/restore_view.vim'
* Bundle 'airblade/vim-gitgutter'
* Bundle 'tpope/vim-abolish.git'
* Bundle 'tpope/vim-markdown'
* Bundle 'spf13/vim-preview'
* Bundle 'tpope/vim-cucumber'
* Bundle 'quentindecock/vim-cucumber-align-pipes'
* Bundle 'Puppet-Syntax-Highlighting'

