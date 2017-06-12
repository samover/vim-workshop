# README

## Getting started

- `brew update && brew install vim`

- Install plugin manager [Vim Plug](https://github.com/junegunn/vim-plug)

- Save [vimrc.example](./vimrc.example) to `$HOME/.vimrc`

- Open vim: `vim`

- Install plugins: `:PlugInstall`

- Open your .vimrc: `:e ~/.vimrc`

## Modal editing

### NORMAL MODE

- Use <ESC> to get into normal mode

- File navigation

- Recommended plugin: https://github.com/takac/vim-hardtime

### INSERT MODE

- Use `i` to enter insert mode

- File editing

### VISUAL MODE

- Use `v` to enter visual mode

- Object selection

### COMMAND MODE

- Use `:` to enter command mode

- Ex commands

## VIM LANGUAGE

- VERBS:
    - d: delete (char, D: line)
    - c: change (char, C: line)
    - y: yank ( = copy )
    - v: visually select (char, V: line)

- MODIFIERS
    - i: inside
    - a: around
    - NUM: number
    - t: search and stop before
    - f: search and land on it
    - /: find a string (regex)

- NOUNS
    - w: word
    - s or ): sentence
    - p or }: paragraph
    - t: tag (think HTML/XML)
    - b: block (think programming)

- A full sentence consists of VERB MODIFIER NOUN

### Getting to know the basics
- https://vim-adventures.com/
- http://www.vimgenius.com/

### Advanced vimming
- https://vimgifs.com/
- https://danielmiessler.com/study/vim/
- http://vimgolf.com/

## BASIC COMMANDS

- Save file: `:w`
- Save file and quit: `:wq` or `ZZ`
- Quit without saving: `:q!`
- Move vim to background: `C-z`
- Move vim to foreground: `fg`
- Execute shell commands: `!mkdir -p hello/world`

## SEARCH AND REPLACE TEXT

- `/bar`
- You can use regular expressions: `/[bz]ar`
- Replace text in file with: `:%s/bar/foo/g`
- Or replace in next three lines: `3V:s/bar/foo/g`
