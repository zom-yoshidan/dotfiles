dotfiles
========

manage dotfiles

## Usage

### create dotfiles(make symlink)

If you clone this repository at /home/dotfiles

```````
sh ~/dotfiles/setup.sh dotfiles
```````
You will have ~/.vimrc, ~/.zshrc and more.

When remove dotfiles (only symlinks)
```````
sh ~/dotfiles/setup.sh dotfiles cleanup
```````


### setup vim(plugin install)

If you clone this repository at /home/dotfiles

```````
sh ~/dotfiles/setup.sh vimenv
```````

You will have some plugin for vim. (for example "nerdtree", "unite" and more)  


With refe (for ruby developer)
```````
sh ~/dotfiles/setup.sh vimenv ruby
```````
