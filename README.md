dotfiles-local
==============

Follow these steps: <br />
1. Follow the instructions here: [thoughtbot/laptop](https://github.com/thoughtbot/laptop)<br />
2. and here: [thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles)<br />
3. run: ``$ git clone https://github.com/betoharres/dotfiles-local.git ~/``<br />
4. and: ``$ find ~/dotfiles-local -name "*.local" -exec bash -c 'ln -s $0 ~/' {} \;``<br />

## Custom changes
* ``$ gc Blah Blah Blah`` alias to: ``git commit -m "Blah Blah Blah"``
