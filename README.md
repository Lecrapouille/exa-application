# Exa-Application

Python3 script for compiling application for https://github.com/exaequos for Linux, Windows and Mac OSX.
The application is [CEF](https://bitbucket.org/chromiumembedded/cef/wiki/Home) based.

## Compilation

```
python3 -m pip install -r requirements.txt
python3 build.py
```

The `ExaequOS/` folder with all its artfacts shall have been created. To start the `ExaequOS` application

```
cd ExaequOS
./ExaequOS
# or:
# LD_PRELOAD=libcef.so ./ExaequOS
```
