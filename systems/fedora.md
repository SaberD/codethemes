# Fedora 29 - Gnome terminal
installed-path:
    dnf:
        usr/share/code

install:
    pip3 install codethemes

install issues:
    error building json5:
        - sudo dnf install gcc
        - sudo dnf install gcc-c++ 
        - sudo dnf install python3-devel