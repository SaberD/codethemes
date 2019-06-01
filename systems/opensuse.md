# Opensuse - KDE Konsole terminal
installed-path:
    zypper:
        usr/share/code

install:
    @root pip install codethemes

install issues:
    pyjson5 issue (gcc no usch file or directory):
        sudo zypper install gcc
        sudo zypper install gcc-c++
        sudo zypper install python3-deve

output:
    cannot use dconf (for Konsole)
    themes are stored in 