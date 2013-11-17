# Clone from  Thomas Hunter's VIM Configuration

## Features

* File Browser on left side of screen
* Functions, Variables, Classes on right
* Move between buffers in center screen
* View status of the current GIT repo (if applicable)
* Special features when running under MacVIM
* Autocomplimentation php,css,html,js

### Switching between files (Buffers)

* Use _,q_ to close the current file (a different file will appear in its place)
* Use _Ctrl h Ctrl l_ to move between open files
 * _Ctrl Left Ctrl Right_ also works for switching between files
 * While in MacVim, you can swipe left and right to switch between open files

### Viewports (Windows)

* Use _,h ,j ,k ,l_ to navigate between viewports
* Use _,Q_ to close the current window (you probably won't ever need to do this)
* Use _,n_ to toggle the file browser
* Use _,y_ to toggle the tag browser
* Use _,t_ or _Cmd+T_ to perform a recursive fuzzy filename search
* Use _,a_ and type a phrase to search to search based on content within your files (quote and escape if needed)
* Use _,A_ to close the open ack search results at the bottom of the screen (same going down, closing, going right, e.g. _,j ,Q ,l_)

### File Browser (NERDTree)

* Use _,n_ to toggle the file browser
* Use standard movement keys to move around
* Use _Ctrl j_ and _Ctrl k_ to move between siblings (aka skip over children in expanded folders)
* Use _C_ to make the highlighted node the current working directory
* Use _:Bookmark BookmarkName_ to bookmark the current selection
* Use _B_ to toggle the bookmark menu
* Use _?_ if you'd like some NERDTree documentation

### Tag Browser (Tag List)

* Use _y_ to toggle the tag browser viewport
* Use _s_ to reorder the items by alpha or occurance

## Requirements

* Install ctags and configure on your Mac: http://thomashunter.name/blog/installing-vim-taglist-with-macvim-in-os-x/

## Installation

Run these commands in your terminal to fully install this vim setup within OS X. It will probably require some
tweaking to get it working under Linux.

    cd ~
    git clone ?? .vim
    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc

## Screenshots

![Screenshot](http://thomashunter.name/pictures/macvim.png "Screenshot of MacVIM")
