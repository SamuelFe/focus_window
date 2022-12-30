# Independent directional focus control
The objective of this project is to provide a simple script (POSIX compliant preferably) that allows the user to bind some key to change focus to the window at ( left | right | up | down )

# Why
I'm using Openbox Window Manager and it only has the option to bind some key to `NextWindow` command, the standard Alt-Tab behavior.

I still want to use Openbox but I want be able to change focus the way Tiling Window Managers do (or the closest possivle).

# Usability
`focus_window --left` change focus to window at left

`focus_window --right` change focus to window at right

`focus_window --up` change focus to upper window

`focus_window --down` change focus to window below

# Installation
1. Put the script in yout path, moving it to `/usr/local/bin/` may do the trick
2. Set bindings to the commands accordingly to your settup (or with `sxhkd` for for an independent aproach)

