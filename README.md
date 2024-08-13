# tomorrow-night-deepblue (Vim and Neovim color scheme)
![License](https://img.shields.io/github/license/jamescherti/vim-tomorrow-night-deepblue)

The Vim color scheme **Tomorrow Night Deepblue** is a beautiful deep blue variant of the Tomorrow Night color scheme, which is renowned for its elegant color palette that is pleasing to the eyes (The colorscheme was previously called tomorrow-night-seablue).

The **Tomorrow Night Deepblue** colorscheme features a deep blue background color that creates a calming atmosphere. The contrasting colors make it easy to distinguish between different elements of your code. The tomorrow-night-deepblue colorscheme is also a great choice for programmer who miss the blue themes that were trendy a few years ago.

![](https://raw.githubusercontent.com/jamescherti/vim-tomorrow-night-deepblue/master/.screenshot.png)


## Authors

Maintainers: [James Cherti](https://www.jamescherti.com/)

The tomorrow-night-deepblue color scheme is based on Tomorrow Night Blue by Chris Kempson.

## Installation

### Vim

#### Installation with Vim's built-in package manager (Vim 8 and above)

```bash
mkdir -p ~/.vim/pack/jamescherti/start
cd ~/.vim/pack/jamescherti/start
git clone --depth 1 https://github.com/jamescherti/vim-tomorrow-night-deepblue
vim -u NONE -c "helptags vim-tomorrow-night-deepblue/doc" -c q
```

### Neovim

The theme is also compatible with Neovim. The Tomorrow Night Deepblue colorscheme can be installed in Neovim with this one-liner:
```
mkdir -p ~/.config/nvim/colors &&  cd ~/.config/nvim/colors && curl -o tomorrow-night-deepblue.vim https://raw.githubusercontent.com/jamescherti/vim-tomorrow-night-deepblue/master/colors/tomorrow-night-deepblue.vim
```

## Activate the color scheme

```viml
:color tomorrow-night-deepblue
```

## Links
- Git repository: [jamescherti/vim-tomorrow-night-deepblue](https://github.com/jamescherti/vim-tomorrow-night-deepblue)
- [Announcement in James Cherti's website about the Vim color scheme Tomorrow Night Deepblue](https://www.jamescherti.com/vim-tomorrow-night-seablue-theme-color-scheme/)
- There is also an Emacs version of this theme: [Emacs Theme: Tomorrow Night Deepblue](https://www.jamescherti.com/emacs-tomorrow-night-deepblue-theme-a-refreshing-color-scheme-with-a-deep-blue-background/)
