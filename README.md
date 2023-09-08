# xpywm_mod

This is xpywm a Window Manager for the X window system, written in python by Hiroyuki Ohsaki
found here: https://pypi.org/project/xpywm/

I have made some modifications to the source code mainly cursor positioning, titlebar and frame hiding, auto layout sizes, hotkeys, and
using Mod4 for moving and resizing windows. 

install xpywm by typing at a terminal prompt (do not add sudo):  pip install xpywm

(this command will also install python-xlib if needed to your home folder)

replace the xpywm file at $HOME/.local/bin with the new one.

edit your .xinitrc or .xsession file to add:  python3 ~/.local/bin/xpywm
