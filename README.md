# .vimrc

## Installation

Checkout the project:

```sh
git clone https://github.com/tobyjsullivan/vimrc.git
```

Add the .vimrc file to your profile directory (change the checkout directory as needed):

```sh
ln -s ~/projects/vimrc/.vimrc ~/.vimrc
ln -s ~/projects/vimrc/.vim ~/.vim
```

### YouCompleteMe

The YouCompleteMe plugin has some specific install steps. Check [their 
documentation](https://github.com/Valloric/YouCompleteMe/blob/master/README.md#installation) for details.

## Installing plugins

Pathogen is used for plugin management.

Install plugins by checking them out to the `.vim/bundles` directory. 
E.g., `git clone https://github.com/junegunn/fzf ~/.vim/bundles/fzf`
