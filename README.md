# shell_setup

## Change Default Shell

```
chsh -s /bin/zsh
```

## Install zsh
URL to install: https://ohmyz.sh/

But most likely it is
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```



## Install Plug Ins
Install plugin manager here: https://github.com/junegunn/vim-plug
``` curl -fLo ~/.vim/autoload/plug.vim --create-dirs \\n    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim```

```vim ~/.vimrc```

Add to `~/.vim/colors` the molokai color https://github.com/tomasr/molokai

Then go in and run `:PlugInstall` in vim

Copy in theme
```cp ~/projects/shell_setup/alex.zsh-theme ~/.oh-my-zsh/themes/```
Update oh-my-zsh to use the new theme of "alex"

Then
```source ~/.zshrc```

