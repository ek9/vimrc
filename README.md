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

## Authors

Copyright (c) 2015-2016 ek9 <dev@ek9.co> (https://ek9.co). Copyright (c) Tim
Pope for parts of code from [tpope/vim-sensible][1] project.

[0]: https://github.com/ek9/vimrc
[1]: https://github.com/tpope/vim-sensible
