# vim

cat ~/.vimrc
```vim
filetype plugin indent on
syntax on
set backspace=indent,eol,start
set number relativenumber " set nu rnu
set wildmenu
```

search the help section:
```vim
helpgrep
copen
cclose
```

Start vim without any config:
```bash
vim -u NONE
```

Start vim with the following commands:
```bash
vim -c "help | only"
```

vimhelp function:
```bash
function vimhelp() {
  vim -u NONE -c "help $1 | only | syntax enable";
}
```
