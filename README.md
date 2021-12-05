# st - simple/suckless terminal
st is a simple terminal implementation for X.

## Patches
This is my custom st build. It contains these patches:
+ [alpha](https://st.suckless.org/patches/alpha/)
+ [alpha-focus-highlight](https://st.suckless.org/patches/alpha_focus_highlight/)
+ [boldisnotbright](https://st.suckless.org/patches/bold-is-not-bright/)
+ [boxdraw](https://st.suckless.org/patches/boxdraw/)
+ [font2](https://st.suckless.org/patches/font2/)
+ [hidecursor](https://st.suckless.org/patches/hidecursor/)
+ [newterm](https://st.suckless.org/patches/newterm/)
+ [scrollback](https://st.suckless.org/patches/scrollback/)
+ [undercurl](https://st.suckless.org/patches/undercurl/)
+ [netwmicon](https://st.suckless.org/patches/netwmicon/)
+ [desktopentry](https://st.suckless.org/patches/desktopentry/)

## Installation
Edit config.mk file to match your local setup (st is installed into the `/usr/local` namespace by default).

Afterwards enter the following command to build and install st:
```
sudo make install clean
```

## Uninstallation
To uninstall st, go to source code folder and run the following command:
```
sudo make uninstall
```

## Basic keybindings

| Key binding           |                      Action                                                       |
| ----------------------|:---------------------------------------------------------------------------------:|
| Ctrl + Shift + c      | Copy selected text                                                                |
| Ctrl + Shift + v      | Paste copied text to terminal                                                     |
| Ctrl + Shift + Enter  | Open another terminal (same current working directory as the original terminal)   |
| Ctrl + Up             | Zoom in                                                                           |
| Ctrl + Down           | Zoom out                                                                          |
| Ctrl + Wheel up       | Zoom in                                                                           |
| Ctrl + Wheel down     | Zoom out                                                                          |
| Shift + Up            | Scroll up                                                                         |
| Shift + Down          | Scroll down                                                                       |
| Wheel up              | Scroll up                                                                         |
| Wheel down            | Scroll down                                                                       |
| Shift + PageUp        | Fast scroll up                                                                    |
| Shift + PageDown      | Fast scroll down                                                                  |

## Configuration
The configuration of st is done by editing `config.def.h` file and (re)compiling the source code.
```
sudo make install clean
```
