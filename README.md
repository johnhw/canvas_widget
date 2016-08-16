canvas-widget
===============================

A simple Jupyter HTML5 canvas widget

Installation
------------

To install use pip:

    $ pip install canvas_widget
    $ jupyter nbextension enable --py --sys-prefix canvas_widget


For a development installation (requires npm),

    $ git clone https://github.com/jupyter/canvas-widget.git
    $ cd canvas-widget
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --user canvas_widget
    $ jupyter nbextension enable --py --user canvas_widget
