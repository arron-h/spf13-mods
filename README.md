spf13-mods
==========

My own mods to [spf13's great vim bundle](http://vim.spf13.com). Removed some unneeded features, and changed the completion engine.
Works well on all platforms. On Windows I use [neocomplcache](https://github.com/Shougo/neocomplcache.vim) as opposed to [YouCompleteMe](https://github.com/Valloric/YouCompleteMe).

## Installation

1. Install [spf13-vim](http://vim.spf13.com) as [described](http://vim.spf13.com/#install).
2. Clone this repo to somewhere like`~/spf13-mods`
3. Symlink `.vimrc.local`, `.vimrc.before.local` and `.vimrc.bundles.local` to files of the same name located at `~/`.

Some things you'll need to do once you've done that:

* Download and install a Powerline-patched font from: <https://github.com/Lokaltog/powerline-fonts>. I like Source Code Pro, and it needs to be converted from otf to ttf before it's installed.
  * On OSX it's as simple as downloading, using an online otf>ttf converter, and then opening the font in FontBook and clicking Install.
  * On Linux, use fontforge to convert the font, drop it in ~/.fonts/ and run $sudo fc-cache -f -v
  * On Windows just download, right-click and hit 'Install'.
* Run :BundleClean! and :BundleInstall to add/remove the new bundles.

### Unix-based systems only

* Compile YCM
  * Navigate to ~/.vim/bundles/YouCompleteMe/
  * run ./install.sh --clang-completer

### Optional steps

* Setup JSHint+Syntastic using the following instruction: <http://stackoverflow.com/questions/473478/vim-jslint/5893447#5893447>
