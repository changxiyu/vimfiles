Installation
============

Clone the repo:
``git clone git@github.com:changxiyu/vimfiles.git ~/.vim``

Grab the plugin submodules:
``cd ~/.vim && git submodule init && git submodule update``

Make sure vim finds the vimrc file by either symlinking it:
``ln -s ~/.vim/vimrc ~/.vimrc``

or by sourcing it from your own ~/.vimrc: ``source ~/.vim/vimrc``

PyFlakes_: ``cd ~/.vim/bundle/pyflakes && git submodule init && git submodule update``

Command-T_: ``cd ~/.vim/bundle/Command-T && rake make``

`pep8 <http://pypi.python.org/pypi/pep8>`_: ``sudo easy_install pep8``


Bundled Plugins
===============

-  SnipMate_ snipMate.vim aims to be a concise vim script that implements some of TextMate’s snippets features in Vim.

-  `NERD\_tree`_ A tree explorer plugin for navigating the filesystem

-  pyflakes_ on the fly Python checking in Vim with PyFlakes

-  markdown_ Vim Markdown runtime files

-  Command-T_ The Command-T plug-in for VIM provides an extremely fast, intuitive mechanism for opening files with a minimal number of keystrokes

-  zencoding_ vim plugins for HTML and CSS hi-speed coding

-  rails_ rails.vim: Ruby on Rails power tools

-  Pydiction_ Tab-complete your Python code

-  git-vim_ Plugin files for calling git functions from inside Vim, Syntax files for git displays

-  RST-Tables_ Allows to create and edit restructuredText tables easily

-  `pep8 <https://github.com/vim-scripts/pep8>`_ Check your python source files with `PEP8 <http://www.python.org/dev/peps/pep-0008/>`_

- `supertab <https://github.com/ervandew/supertab>`_ Perform all your vim insert mode completions with Tab

- `css-color-vim <https://github.com/skammer/vim-css-color>`_ Highlight colors in css files 


.. _SnipMate: https://github.com/lxneng/snipmate.vim 
.. _NERD\_tree: https://github.com/scrooloose/nerdtree
.. _pyflakes: https://github.com/kevinw/pyflakes-vim
.. _markdown: https://github.com/tpope/vim-markdown
.. _Command-T: https://github.com/wincent/Command-T
.. _zencoding: https://github.com/mattn/zencoding-vim
.. _rails: https://github.com/tpope/vim-rails
.. _Pydiction: https://github.com/vim-scripts/Pydiction
.. _git-vim: https://github.com/motemen/git-vim
.. _RST-Tables: https://github.com/vim-scripts/RST-Tables
.. _pep8: https://github.com/vim-scripts/pep8
