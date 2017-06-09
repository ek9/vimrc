ek9/vimrc
=========

[ek9/vimrc][0] is a personal `.vimrc` configuration published as a vim plugin.
It is inspired by [tpope/vim-sensible][1].

Part of [ek9/dotfiles][10] collection.

## Install

Install `ek9/vimrc` using [vim-plug][2]:

```vim
call plug#begin()
Plug 'ek9/vimrc'
call plug#end()
```

You can also use [Vundle][3] or [Pathogen][4].

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
- Disable default behaviour of paste writing overwritting content to clipboard


## Hotkeys

Hotkeys and aliases added by this config:

- Disable arrow keys (to force use of `h/j/k/l`)
- Enable tab navitagion with Ctrl+h/j/k/l
- Enable split window navigation with Shift+h/j/k/l
- `Ctrl+s` split window vertically
- `Ctrl+v` split window horizontally
- `<`/`>` adjust the size of split windows
- Disable `F1` / `Q` help keys
- `F1` toggle spellcheck
- `F2` toggle paste mode
- `F3` toggle line numbers
- `F4` toggle gundo
- `F5` toggle whitespace display
- `Ctrl+L` - line open/close
- `:w!!` - write file with `sudo`

## Authors

Copyright (c) 2015-2016 ek9 <dev@ek9.co> (https://ek9.co). Copyright (c) Tim
Pope for parts of code from [tpope/vim-sensible][1] project.

[0]: https://github.com/ek9/vimrc
[1]: https://github.com/tpope/vim-sensible
[2]: https://github.com/junegunn/vim-plug
[3]: https://github.com/VundleVim/Vundle.vim
[4]: https://github.com/tpope/vim-pathogen
[10]: https://github.com/ek9/dotfiles
