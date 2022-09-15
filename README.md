# ipytelegram_widget

Jupyter widget for use telegram.js in Voila WebApp

## Installation

To install use pip:

    $ pip install ipytelegram_widget

For a development installation (requires [Node.js](https://nodejs.org) and [Yarn version 1](https://classic.yarnpkg.com/)),

    $ git clone https://github.com/Alzo.ru/ipytelegram_widget.git
    $ cd ipytelegram_widget
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --overwrite --sys-prefix ipytelegram_widget
    $ jupyter nbextension enable --py --sys-prefix ipytelegram_widget

When actively developing your extension for JupyterLab, run the command:

    $ jupyter labextension develop --overwrite ipytelegram_widget

Then you need to rebuild the JS when you make a code change:

    $ cd js
    $ yarn run build

You then need to refresh the JupyterLab page when your javascript changes.
