![plastic.vim](https://github.com/MomePP/plastic.vim/blob/master/plastic-vim-screen.png)

# plastic.vim

[VSCode Plastic](https://github.com/will-stone/plastic) theme port for vim/neovim.

- This fork remove background color, so i can set the background from iTerm itself.

## Install

1. Using your plugin manager of choice and placing `MomePP/plastic.vim` in your .vimrc file.
   or
2. clone this directory into your vim/plugged directory

```vim
" important:
set termguicolors

set background=dark
syntax on
colorscheme plastic

" Lightline
let g:lightline = { 'colorscheme': 'plastic' }
```

