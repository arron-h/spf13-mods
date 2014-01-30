spf13-mods
==========

My own mods to spf13's great vim bundle. Removed some unneeded features, and changed the completion engine.

Installation
============

Just drop these files at ~/.
Some things you'll need to do once you've done that:
* Download and install a Powerline-patched font from: <https://github.com/Lokaltog/powerline-fonts>
  * I like Source Code Pro, and it needs to be converted from otf to ttf before it's installed.
  * On OSX it's as simple as downloading, using an online otf>ttf converter, and then opening the font in FontBook and clicking Install.
  * On Linux, use fontforge to convert the font, drop it in ~/.fonts/ and run $sudo fc-cache -f -v
* Run :BundleClean! and :BundleInstall to add/remove the new bundles.
* Compile YCM
  * Navigate to ~/.vim/bundles/YouCompleteMe/
  * run ./install.sh --clang-completer
* Optional:
  * Setup JSHint+Syntastic using the following instruction: <http://stackoverflow.com/questions/473478/vim-jslint/5893447#5893447>

