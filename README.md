dotfiles-local
==============

Follow these steps: 
1. Follow the instructions here: [thoughtbot/laptop](https://github.com/thoughtbot/laptop)
2. and here: [thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles)
3. run: ``$ git clone https://github.com/betoharres/dotfiles-local.git ~/``
4. and: ``$ find ~/dotfiles-local -name "*.local" -exec bash -c 'ln -s $0 ~/' {} \;``
