# Dracula Pro Vim Theme

**Premium dark color scheme for Vim with Airline & Lightline support.**

## Installation

```vim
call plug#begin('~/.vim/plugged')
Plug 'Mora1n/dracula-pro-vim', { 'as': 'dracula_pro' }
call plug#end()

if has('termguicolors') | set termguicolors | endif
set background=dark
colorscheme dracula_pro

" Airline: let g:airline_theme='dracula_pro'
" Lightline: let g:lightline={'colorscheme':'dracula_pro'}
```

Or with Vim 8+ packages:

```bash
cd ~/.vim/pack/vendor/start
git clone https://github.com/Mora1n/dracula-pro-vim.git
```

## Configuration

Set (before `colorscheme`) to toggle features:

```vim
let g:dracula_bold      = 1
let g:dracula_italic    = 1
let g:dracula_underline = 1
let g:dracula_undercurl = 1
let g:dracula_colorterm = 1
```

## License

[Dracula EULA](https://gum.co/dracula-pro)
