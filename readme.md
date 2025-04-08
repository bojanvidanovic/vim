# Vim config

## Clone

```
git clone https://github.com/bojanvidanovic/vim.git ./.dotfiles/vim
```

## Create a symlink to the .vimrc

```
ln -s ~/.dotfiles/vim/.vimrc ~/.vimrc
```

## Install Plug

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

## Install COC Extensions

```
:CocInstall coc-json coc-tsserver coc-eslint coc-css coc-html coc-stylelint coc-tslint coc-markdownlint coc-svg coc-tailwindcss coc-yaml coc-copilot
```
