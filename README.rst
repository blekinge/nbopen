Open notebooks from the command line

nbopen looks for the nearest running notebook server - if it finds one, it
opens a web browser to that notebook. If not, it starts a new notebook server
in that directory.

Installation::

    pip install nbopen

Usage::

    nbopen AwesomeNotebook.ipynb

To integrate with your file manager, so you can double click on notebooks
to open them, run:

* Linux/BSD: ``python -m nbopen.install_xdg``.
* Windows: ``python -m nbopen.install_win``
* Mac: Clone the repository and run ``./osx-install.sh``
