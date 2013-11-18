## Quicking start

### OSX

Get started:

    Install xcode command line tools
    xcode-select --install

Buildout:

    pip install cython
    python bootstrap.py
    ./bin/buildout

Run:

    kivy ./bin/py plasma.py <--- Or whatever kivent app.


## Windows

Get started:

    Install visual studio 2008
    http://www.microsoft.com/en-au/download/details.aspx?id=7873

Buildout:

    . /c/path/to/kivy/kivyenv.sh
    pip install cython
    python bootstrap.py
    ./bin/buildout

Run:

    . /c/path/to/kivy/kivyenv.sh
    ./bin/py plasma.py <-- Or whatever kivent app.

Didn't work? Make sure you did '. /c/kivy/kivyenv.sh', otherwise the environment
variables won't be loaded. Check with 'echo $PYTHONPATH'; it should contain a
reference to the kivy folder.
