# VimFile 

Arquivo de configuração do editor VIM.
Este arquivo teve como base o arquivo de
[Repositorio do Avelino](https://github.com/avelino/vim-bootstrap)


### Linux

* Ubuntu

```
$ sudo apt-get install git exuberant-ctags ncurses-term
```

* pyflakes (optionally for python bundles)
```
$ pip install flake8
```
* Requisitos para o plugin YouCompleteMe
```
$ sudo apt-get install build-essential cmake
$ sudo apt-get install python-dev
$ cd ~/.vim/bundle/YouCompleteMe
$ ./install.sh --clang-completer
```



## Commands

Commands | Descriptions
--- | ---
`:cd <path>` | Open path */path*
`<Control+w>+arrows` | Navigate via split panels
`<Control>+w+w` | Alternative navigate vim split panels
`,.` | Set path working directory
`,w or ,x` | Next buffer navigate
`,q or ,z` | previous buffer navigate
`SHIFT+t` | Create a tab
`TAB` | next tab navigate
`TAB` insert mode | complete word
`SHIFT+TAB` | previous tab navigate
`<Control> + p` | Find and open files
`<Control> + j` insert mode | complete snippets
`,b` | Find file on buffer (open file)
`,c` | Close active buffer (clone file)
`F2`  | Open tree navigate in actual opened file
`F3`  | Open/Close tree navigate files
`F4` | List all class and method, support for python, go, lua, ruby and php
`F5`  | Open color picker 
`,v` | Split vertical
`,h` | Split horizontal
`,f` | Search in the project
`,o` | Open github file/line (website), if used git in **github**
`,sh` | Open shell terminal inside Vim
`,ga` | Execute *git add* on current file
`,gc` | git commit (splits window to write commit message)
`,gsh` | git push
`,gll` | git pull
`,gs` | git status
`,gb` | git blame
`,gd` | git diff
`,gr` | git remove
`>` | indent to right
`<` | indent to left
`gc` | Comment or uncomment lines that {motion} moves over
`YY` | Copy to clipboard
`P` | Paste
`<Control+y>,` | Activate Emmet plugin

## Python hotkeys

Commands | Descriptions
--- | ---
`SHIFT+k` | Open documentation
`Control+Space` | Autocomplete
`,d` | Go to the Class/Method definition
`,r` | Rename object definition
`,n` | Show where command is usage

## Installation

* Download your own vimrc file at http://www.vim-bootstrap.com
* Put your vimrc file (or nvimrc if you use NeoVim) into home folder
```
mv ~/Downloads/vimrc ~/.vimrc
```
* Execute ViM and it will install plugins automatically
```
vim +NeoBundleInstall +qall
```

## Updating to the latest version

    :VimBootstrapUpdate (thanks to @sherzberg)
    :NeoBundleUpdate

## Learn Vim

Visit the following sites to learn more about Vim:

* [Learn Vim Progressively](http://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/)
* [Vim Adventures](http://vim-adventures.com/)
* [Vimcasts](http://vimcasts.org)
* [Using Vim as a Complete Ruby on Rails IDE](http://biodegradablegeek.com/2007/12/using-vim-as-a-complete-ruby-on-rails-ide/)
* [Why, oh WHY, do those #?@! nutheads use vi?](http://www.viemu.com/a-why-vi-vim.html)
* [Byte of Vim](http://www.swaroopch.com/notes/Vim)
* [Screencast "17 tips for Vim" (in portuguese)](http://blog.lucascaton.com.br/?p=1081)
