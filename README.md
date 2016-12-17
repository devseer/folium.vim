# Folium
Word count, page count and progress tracker for Vim

## Installation
### [Vundle](https://github.com/VundleVim/Vundle.vim)
1. Add `Bundle 'devseer/folium.vim'` to your `.vimrc`
2. Run `:PluginInstall`

### [Plug](https://github.com/junegunn/vim-plug)
1. Add `Plug 'devseer/folium.vim'` to your `.vimrc`
2. Run `:PlugInstall`

### [Pathogen](https://github.com/tpope/vim-pathogen)
`git clone https://github.com/devseer/folium.vim ~/.vim/bundle/folium.vim`

## Configuration
### Setting the word count per page
Add `let wpp=200` to your `.vimrc`, where `200` specifies the number of words per page.

## Roadmap
* Current page number
* Current session word/page count
* Play nice with statusbar plugins eg. airline
