vim-nellys-star
===========

Refined and subdued monokai color scheme for vim under an MIT license.
The original code is from crusoexia (of which this is a fork).

Install
-------

### [vim-plug](https://github.com/junegunn/vim-plug) (recommend)

    Plug 'rumschuettel/vim-nellys-star'

### Manually

Download the [colors/nellys-star.vim](https://raw.githubusercontent.com/rumschuettel/vim-nellys-star/master/colors/nellys-star.vim) file, move it into your __~/.vim/syntax/__ folder.

Usage
-----

Copy below command to your `~/.vimrc`:

```VimL
syntax on
colorscheme nellys-star 
set t_Co=256  " vim-nellys-star only supports 256 colours in terminal.
```

Configuration
-------------

### Italic

By default the gui enables italic but terminal. They both can be configured.
    
If you are using a font support italic, paste below command in `.vimrc` to turn on terminal italic:

    let g:nellys_star_term_italic = 1
    let g:nellys_star_gui_italic = 1

