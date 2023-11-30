# Browser application rendering ExaequOS

Python3 script compiling the browser application rendering the online version of
[ExaequOS](https://github.com/exaequos).

## Compilation

Compile for Linux, Windows and Mac OSX.

```
python3 -m pip install -r requirements.txt
python3 build.py
```

The `ExaequOS/` folder with all its artfacts shall have been created.

## Running

To start the `ExaequOS` application:

```
cd ExaequOS
./ExaequOS
# or:
# LD_PRELOAD=libcef.so ./ExaequOS
```
