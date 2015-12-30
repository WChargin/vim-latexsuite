# Purpose

This repository exists for easy use with [vim-plug][] and so you don't have to work with Sourceforge, which (last time I checked) is now including malware with its installers.

I just downloaded the vim-latex-1.8.23-20141116.812-gitd0f31c9 release [from Sourceforge][release] and committed it.

# Usage

Add the following to your .vimrc:

```vim
call plug#begin('~/.vim/plugged')
" other plugins...
Plug 'wchargin/vim-latexsuite', { 'for': 'tex' }
call plug#end()
```

  [vim-plug]: https://github.com/junegunn/vim-plug
  [release]: http://sourceforge.net/projects/vim-latex/files/snapshots/
