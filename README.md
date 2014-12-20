dotfiles-local
==============
Run after clonning into ~/
```Shell
find ~/dotfiles-local -name "*.local" -exec bash -c 'ln -s $0 ~/' {} \;
```
