# Pebble Tool

Available from Rebble project page https://github.com/pebble-dev/pebble-tool/

Definitely works with Python 2.7.

## Windows note

Windows is NOT a supported platform for Pebble (outside of WSL).

However you can get debug trace on native Windows using Python 2.7
by checking out the code and issuing:

    python -m pip install -r requirements_py27win.txt

Debug trace can be accessed via:

    python pebble.py logs --phone IP_ADDRESS_HERE

Alternatively `setup.py` can be called with the usual `develop` or `install`
parameter.
