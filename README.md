ek9/vimrc
=========

[ek9/vimrc][0] is a personal `.vimrc` configuration published as a pathogen /
vundle plugin. It is inspired by [tpope/vim-sensible][1].

## Install

Install `ek9/vimrc` using Vundle:

```vim
"" vundle setup - keep this at the very start
filetype off
set rtp+=~/.vim/bundle/vundle/
call vundle#rc()
filetype plugin indent on
Bundle 'gmarik/vundle'

"" plugins
" generic config
Bundle 'ek9/vimrc'
```

Start `vim` and exeecute `:BundleInstall`.

*Note!* Make sure vundle is installed in `~/.vim.bundle/vundle`.

## Features

This `vimrc` plugin enables the following features and tweaks:

- Tweaks from [tpope/vim-sensible][1]:
    - Enable UTF-8
    - Use vi iMproved (`nocompatible`)
    - Always show statusline
    - Show type commands
    - Automatically refresh changed files (with confirmation)
    - Increase history to 1000
    - Enable live search
    - Enable `autoindent` (preserve indentation)
    - Enable `smarttab` (tabs as spaces)
    - Smart backspace handling
    - Syntax highlighting enabled
- Mouse and visual bell features disabled
- Enable fast tty redraw
- Window splitting defaults to below (instead of top) and right (instead of left)
- Unified backup, undo and vimfile directories (under `/tmp/vim-$USER/`)
- Swap files disabled
- Display tweaked to use 16 colors
- Enable auto-wrap at 80 column width (with visual vertical line enabled)
- Enable highlight of current cursorline
- Scrolloff set to 5 lines
- Enable title updating
- Enable line numbers
- Enabled smart case sensitivity in searching
- Use 4 spaces for tabs as default with 2 spaces for `html,twig,pp,sls` files.
- Enable `expandtab`
- Spelling language set to `en`.
- Word wrap tweaked to wrap only whole words and not cut them
- Search tweaks to highlight results, ignore casing, starts showing results as
  you search.
- Find and replace is global by default
    
## Authors

Copyright (c) 2015-2016 ek9 <dev@ek9.co> (https://ek9.co). Copyright (c) Tim
Pope for parts of code from [tpope/vim-sensible][1] project.

[0]: https://github.com/ek9/vimrc
[1]: https://github.com/tpope/vim-sensible
