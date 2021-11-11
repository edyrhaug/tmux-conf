# tmux-conf
A simple tmux config, including a colorscheme and preset exported from vim using [vim-airline](https://github.com/vim-airline/vim-airline) and [tmuxline.vim](https://github.com/edkolev/tmuxline.vim).

This setup requires that you patch the [powerline glyphs](https://github.com/powerline/powerline/blob/develop/font/PowerlineSymbols.otf) on to the font you are using, or that you download and switch to a [font that already has these fonts](https://github.com/powerline/fonts).

## Installation

```
git clone git@github.com:edyrhaug/tmux-conf.git ~/.tmux
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
ln -s ~/.tmux/tmux.conf ~/.tmux.conf
```
