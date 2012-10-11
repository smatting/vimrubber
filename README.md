vimrubber
=========

This plugin sets ``errorformat'' for *.tex files so that it is compatible with the output of ``rubber -s''.
To see how to use the Rubber LaTeX build system with vim see [vim.wikia.com](http://vim.wikia.com/wiki/Compiling_LaTeX_from_Vim).

# Install
If you use [Vundle](https://github.com/gmarik/vundle/) to manage vim plugins just add
    Bundle 'smatting/vimrubber'
to your ``~/.vimrc''.

To install it manually just copy ``autoload/vimrubber.tex'' into ``~/.vim/autoload/''.

# Usage
When building your LaTeX project with rubber the messages in the quickfix window should look fine now.
