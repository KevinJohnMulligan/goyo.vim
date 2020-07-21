Soft-wrapper
============

This is a paired down version of the original goyo.vim with the aim of only providing a soft-wrap functionality using an empty window to the right of the desired text. Another change was having hybrid line numbers (relative line numbers and absolute line numbers) in both normal and insert modes. The main reason for the line numbers in insert mode is to maintain the position of the text, otherwise, it moves off to the left when entering insert mode.

The following screenshots show examples of these features. My ([init.vim](https://github.com/KevinJohnMulligan/nvim)) is setup to change colour depending on the mode, so that it is very obvious whether or not I'm in normal or insert mode.

These modifications were done quickly and have not been fully bug tested.

goyo.vim ([고요](http://en.wiktionary.org/wiki/고요하다))
=========================================================
([The original code can be found here:   https://github.com/junegunn/goyo.vim/](https://github.com/junegunn/goyo.vim/))
