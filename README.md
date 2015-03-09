# Vim setup for web development 
This is tailored to my needs (mostly frontend) and thus probably won't work well for everyone.

## Plugins
See [bundle](https://github.com/davidyezsetz/.vim/tree/master/bundle)

## Installation
1. Back up `~/.vim`
2. Remove `rm -rf ~/.vim`
3. Make sure you're in your home folder `cd ~`
4. Get the setup `git clone --recursive https://github.com/davidyezsetz/.vim.git`
5. Symlink Vim configuration to home folder `ln -s ~/.vim/.vimrc .vimrc`
6. Install patched powerline fonts: https://github.com/powerline/fonts (dependancy for Airline)
7. Install Exuberant CTAGs (dependency for Tagbar)
8. Install YouCompleteMe dependencies https://github.com/Valloric/YouCompleteMe

## Updates
1. Run `./update`

## Educational Resources
- http://www.integralist.co.uk/posts/vim-workflow/
- http://walking-without-crutches.heroku.com/image/images/vi-vim-cheat-sheet.png
- http://yanpritzker.com/2011/12/16/learn-to-speak-vim-verbs-nouns-and-modifiers/
- https://github.com/joyent/node/wiki/Vim-Plugins
- http://vimcasts.org/episodes/archive
- http://derekwyatt.org/vim/tutorials/novice/#Welcome
- http://usevim.com/2012/04/13/registers/
