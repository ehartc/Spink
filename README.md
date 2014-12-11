Spink 
=========================
I haven't found any colorscheme with decent syntax highlighting. So I created Spink pretty quickly.  
This plugin works properly with Xterm emulators on X Window System (not cterm), MacVim and gVim.

Currently it's geared towards Python, PHP, HTML5, SASS/CSS and general Javascript.   
I don't use this plugin anymore after I switched to GNU Emacs.

To let others use it, Spink is published now. Enjoy!

## Usage

You can install Spink with whatever package manager you use. For example:

``` viml
" vim-plug
Plug 'Junza/Spink'
" NeoBundle
NeoBundle 'Junza/Spink'
" Vundle
Plugin 'Junza/Spink'
```

If you don't use a plugin manager just copy the content to `~/.vim/`.

When you have the plugin installed, you can set it in your `vimrc`.

#### Compatibiltiy.
Spink supports some plugins, like Unite, Syntastic and Easymotion out of the box.
