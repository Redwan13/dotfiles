# dotfiles

Collection of dotfiles and other system configs.

* Vim - config is targeted to neovim, but the only difference is Vundle bundles path.
  * Don't forget to install [Vundle](https://github.com/VundleVim/Vundle.vim) to install all other plugins.
  * Autocomplete [YouCompleteMe](https://github.com/Valloric/YouCompleteMe). Read its manual, damn you.
  * Vim-airline uses powerline fonts.
    * Fonts can be downloaded [here](https://github.com/powerline/fonts)...
    * Or disabled by removing `let g:airline_powerline_fonts=1` in config.
  * Tagbar uses `exuberant-ctags`. They must be installed separatly.
  * install-vim.sh installs neovim with all prereqs
* Awesome - configs for awesome wm.
  * **WORK IN PROGRESS** still not usable.
  * Also submodule with awmtt - testing script for awesome config.
* Other confs (git, svn, tmux) are selfdescribing.
