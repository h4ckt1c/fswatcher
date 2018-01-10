# fswatcher

`fswatcher` is designed to monitor changes of files and trigger defined actions.
This might be useful while programming. In one terminal window your "ide" is opened
and in another window `fswatcher` keeps running. If you save your script/program `fswatcher`
will recognize this and trigger defined actions.

## Usage

    fswatcher python myscript.py

This will monitor myscript.py for changes, executes `python myscript.py` on change and print the
corresponding output.
