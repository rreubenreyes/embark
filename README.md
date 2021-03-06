<p align="center"><img src="Embark.svg" alt="Embark Logo"/></p>

<p align="center"><strong>An ambitious Vim theme.</strong></p>

<p align="center"><em>"Man cannot discover new oceans unless he has the courage to lose sight of the shore. - Andre Gide"</em></p>

![embark screenshot](./embark-screenshot.png)

## Getting Started

> At this time only terminals supporting truecolors will work. Make sure you have `set termguicolors` in your vimrc

First install plugin with your favorite plugin manager.
```
Plug 'skbolton/embark'
```

Then set your colorsheme in vim.
```
colorscheme embark
```

### Lightline support

A lightline theme is also available. Just set your colorscheme to embark.

```
let g:lightline = {
      \ 'colorscheme': 'embark',
      \ }
```

## Configuration

Embark offers a few configuration values to control features. Setting values to `1` will turn the feature on.

Italics - Make sure your terminal is set up to handle them. See [this](https://medium.com/@dubistkomisch/how-to-actually-get-italics-and-true-colour-to-work-in-iterm-tmux-vim-9ebe55ebc2be) for help getting italics and true color working in your terminal.

`let g:embark_terminal_italics = 1`


