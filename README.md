# Leaving the CoC behind.

A minimal set up for Nvim using native LSP with some sane defaults and settings.

Uses the latest >=0.5 Neovim

Clone the repository into ~/.config/nvim

Install [ Packer ](https://github.com/wbthomason/packer.nvim)

```bash
git clone https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

## Install language servers

typescript for ts, js, jsx, tsx available from npm

```bash
npm install -g typescript typescript-language-server
```

Lua available in Arch/Manjaro repos

```bash
sudo pacman -S lua-language-server
```

Use VS Code Language server for CSS

```bash
npm i -g vscode-langservers-extracted
```

## eslint_d for linting

```
npm i -g eslint_d
```

## Install formatters

Prettier for html, css, JavaScript etc

```bash
npm i -g prettier
```

lua-fmt

```bash
npm i -g lua-fmt
```

## TODO

- Emmett [maybe with aca/emmet-ls](https://github.com/aca/emmet-ls)
- Auto imports - compe should be able to do this
- Show documentation - lspsaga?
- spelling
- ~~eslint~~
- See what [nvim-lsp-ts-utils](https://github.com/jose-elias-alvarez/nvim-lsp-ts-utils) can offer
- Styled components highlighting [related to this issue](https://github.com/nvim-treesitter/nvim-treesitter/issues/1111)
- Vue LSP

## Some useful links to help me get this working

[Nvim Lua guide](https://github.com/nanotee/nvim-lua-guide)

[This init.lua is super helpful minmal setup](https://gist.github.com/benfrain/97f2b91087121b2d4ba0dcc4202d252f)

[Getting Eslint working](https://jose-elias-alvarez.medium.com/configuring-neovims-lsp-client-for-typescript-development-5789d58ea9c)

[Lunar Vim for inspiration](https://github.com/ChristianChiarulli/LunarVim)
