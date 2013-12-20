dotfiles
================

Example implementation of a modular, portable dotfile system

Structure
=================

```bash

csim@zappa ~/.dotsplat/repos/dotfiles (master) $ tree -a home
home
├── .bash
│   ├── aliases
│   ├── path
│   ├── path.linux
│   ├── path.mac
│   ├── profile.d
│   │   ├── dotsplat.sh
│   │   ├── linuxVSmac.sh
│   │   ├── prompt.sh
│   │   └── xterm-256color.sh
│   └── prompt
│       └── git-svn-bash.sh
├── .bash_profile
├── .bashrc
├── .screenrc
├── .vim
│   ├── autoload
│   │   └── pathogen.vim
│   ├── bundle
│   │   ├── vim-colors-solarized
│   │   │   ├── autoload
│   │   │   │   └── togglebg.vim
│   │   │   ├── bitmaps
│   │   │   │   └── togglebg.png
│   │   │   ├── colors
│   │   │   │   └── solarized.vim
│   │   │   └── doc
│   │   │       ├── solarized.txt
│   │   │       └── tags
│   │   └── vim-sensible
│   │       ├── README.markdown
│   │       └── plugin
│   │           └── sensible.vim
│   └── colors
│       ├── Tomorrow-Night-Blue.vim
│       ├── Tomorrow-Night-Bright.vim
│       ├── Tomorrow-Night-Eighties.vim
│       ├── Tomorrow-Night.vim
│       ├── Tomorrow.vim
│       └── ir_black.vim
└── .vimrc
```
