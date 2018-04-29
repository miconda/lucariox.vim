# lucariox.vim #

Customized `vim` and `neovim` color scheme inspired from `Lucario` mixed with
`Darkblue` elements and some extra bits.

Original `Lucario` color scheme:

  * https://github.com/raphamorim/lucario

`Darkblue` color scheme is part of default `vim` distribution.

In addition, it defines the colors for terminal, variable types, ...

## Installation ##

Using Pathogen plugin manager:

```
cd .vim/bundle
git clone https://github.com/miconda/lucariox.vim
```

Using `Plug` plugin manager, add to your `.vimrc` or `.config/nvim/init.vim`:

```
Plug 'https://github.com/miconda/lucariox.vim.git
```

Trigger a refresh of your installed plugins.

### Manual Installation ###

For `vim`: copy `colors/lucariox.vim` to `~/.vim/colors/`.

For `neovim`: copy `colors/lucariox.vim` to `~/.config/nvim/colors/`.

## Screenshots ##

### Editor View ###

![Screenshot](https://github.com/miconda/vresources/raw/master/lucariox.vim/screenshots/vim-lucariox-view.png)


### Editor With Terminal View ###

![Screenshot](https://github.com/miconda/vresources/raw/master/lucariox.vim/screenshots/vim-lucariox-terminal.png)

## Remarks ##

  * terminal window is using black background and lightgray foreground colors to
  match the default OS terminal
  * color theme customization was done mainly based on using vim (and friends)
  for C code development
  * initially tested with vim, macvim, neovim and vimr

## License ##

MIT

## Credits ##

Authors and contributors of vim, macvim, gvim, neovim, vimr (and the rest of
the related apps).

The original Lucario theme author and contributors:

  * https://github.com/raphamorim/lucario
