vim-fat-finger
==============

A simple vim plugin that automatically corrects common misspellings and typos as you type.


## Misspellings

This plugin supports over 4,000 common misspellings, as defined in `plugin/fat-finger.vim`.

The settings in the plugin file are defined using Vim's `iabbrev` keyword, which is part of Vim's built-in 
abbreviations feature.  The definitions follow a format of `iabbrev`, followed by the commonly misspelled word, 
and then finally the desired corrected version of misspelling.

For example:
```
iabbrev acheive achieve
iabbrev contraversy controversy
iabbrev demenor demeanor
iabbrev embarass embarrass
iabbrev lisence license
iabbrev morgage mortgage
iabbrev nightfa;; nightfall
iabbrev offred offered
iabbrev precice precise
iabbrev teh the                                                                                                  
```


## Installation

```
git clone git@github.com:chip/vim-fat-finger.git
cp vim-fat-finger/plugin/fat-finger.vim ~/.vim/plugin/
```


## Configuration

Simply edit `~/.vim/plugin/fat-finger.vim` to suit your needs.  If you don't like a specific definition, feel 
free to edit it or remove it altogether.  


## License

[LICENSE](https://github.com/chip/vim-fat-finger/edit/master/LICENSE.md)


## Trolling

Feel free to follow [chip](http://chipcastle.com) on [Github](https://github.com/chip) or 
[Twitter](https://twitter.com/chipcastle)


