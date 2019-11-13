# Vim: one editor for life

> Setup, package manager, and various plug-ins for my configuration of the
> [Vim](http://www.vim.org/index.php) and [Neovim](https://neovim.io/)
> editors [![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)

---

## _How do I use `vimForLife`?_

* For use with _Vim_, clone the configuration in this repo using the following:
  ```bash
  git clone https://github.com/nhejazi/vimForLife.git ~/.vim
  sh ~/.vim/_setup.sh
  ```

- For use with _Neovim_, instead clone the configuration in this repo like so:
  ```bash
  git clone https://github.com/nhejazi/vimForLife.git ~/.config/nvim
  sh ~/.config/nvim/_setup.sh
  ```

- To __install plugins__ with the
[vim-plug](https://github.com/junegunn/vim-plug) manager, see the directions
provided in the `README` of that project.

- To __update plugins__ with the
[vim-plug](https://github.com/junegunn/vim-plug) manager:
  ```vim
  :PlugUpdate
  ```

---

## Plug-ins

_Here is a list of plug-ins currently integrated into this configuration:_

* [`ack.vim`](https://github.com/mileszs/ack.vim)
* [`ale`](https://github.com/w0rp/ale) (Vim v8.0+ and Neovim)
* [`ctrlp.vim`](https://github.com/ctrlpvim/ctrlp.vim)
* [`ditto.vim`](https://github.com/dbmrq/vim-ditto)
* [`goyo.vim`](https://github.com/junegunn/goyo.vim)
* [`gv.vim`](https://github.com/junegunn/gv.vim)
* [`indentLine`](https://github.com/Yggdroot/indentLine)
* [`jedi-vim`](https://github.com/davidhalter/jedi-vim)
* [`lightline`](https://github.com/itchyny/lightline.vim)
* [`lightline-bufferline`](https://github.com/mengelbrecht/lightline-bufferline)
* [`limelight`](https://github.com/junegunn/limelight.vim)
* [`nerdcommenter`](https://github.com/scrooloose/nerdcommenter)
* [`NERDTree`](https://github.com/scrooloose/nerdtree)
* [`Nvim-R`](https://github.com/jalvesaq/Nvim-R)
* [`presenting.vim`](https://github.com/sotte/presenting.vim)
* [`syntastic`](https://github.com/vim-syntastic/syntastic) (Vim pre-v8.0 only)
* [`tmuxline.vim`](https://github.com/edkolev/tmuxline.vim)
* [`tmux-complete.vim`](https://github.com/wellle/tmux-complete.vim)
* [`UltiSnips`](https://github.com/SirVer/ultisnips)
* [`vimtex`](https://github.com/lervag/vimtex)
* [`vim-abolish`](https://github.com/tpope/tpope-vim-abolish)
* [`vim-bracketed-paste`](https://github.com/ConradIrwin/vim-bracketed-paste)
   (Vim only)
* [`vim-css-color`](https://github.com/ap/vim-css-color)
* [`vim-easymotion`](https://github.com/easymotion/vim-easymotion)
* [`vim-eunuch`](https://github.com/tpope/vim-eunuch)
* [`vim-fugitive`](https://github.com/tpope/vim-fugitive)
* [`vim-gitgutter`](https://github.com/airblade/vim-gitgutter)
* [`vim-markdown`](https://github.com/plasticboy/vim-markdown)
* [`vim-mucomplete`](https://github.com/lifepillar/vim-mucomplete)
* [`vim-obsession`](https://github.com/tpope/vim-obsession)
* [`vim-pencil`](https://github.com/reedes/vim-pencil)
* [`vim-polyglot`](https://github.com/sheerun/vim-polyglot)
* [`vim-sensible`](https://github.com/tpope/vim-sensible)
* [`vim-sleuth`](https://github.com/tpope/vim-sleuth)
* [`vim-slime`](https://github.com/jpalardy/vim-slime)
* [`vim-surround`](https://github.com/tpope/vim-surround)
* [`vim-tmux-navigator`](https://github.com/christoomey/vim-tmux-navigator)
* [`vim-visual-multi`](https://github.com/mg979/vim-visual-multi)
* [`vim-wordy`](https://github.com/reedes/vim-wordy)

---

## Colorschemes

_This configuration currently supports several colorscheme options:_

* [Gruvbox](https://github.com/morhetz/gruvbox)
* [Solarized](https://github.com/altercation/vim-colors-solarized)
* [Zenburn](https://github.com/jnurmine/Zenburn)
* [Seoul256](https://github.com/junegunn/seoul256.vim)

---

## Notes

Miscellaneous useful notes and resources:

* [Vim Tips & Tricks](https://bluz71.github.io/2017/05/15/vim-tips-tricks.html)
* [Building a good `vimrc`](https://dougblack.io/words/a-good-vimrc.html#colors)
* [Vim graphical
    tutorial](http://www.viemu.com/a_vi_vim_graphical_cheat_sheet_tutorial.html)

---

## Contributions

These are extremely opinionated and imperfect configurations for Vim and Neovim.
If you would like to contribute to their improvement, a pull request would be
welcome.

---

## Issues

If you encounter any bugs or have any specific feature requests, please [file an
issue](https://github.com/nhejazi/vimForLife/issues).

---

## License

&copy; 2016-2019 [Nima Hejazi](https://nimahejazi.org)

The contents of this repository are distributed under the MIT license. See file
`LICENSE` for details.
