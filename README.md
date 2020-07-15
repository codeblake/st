# Simple Terminal (st)

## Description
A custom build for the suckless [Simple Terminal][st].

:warning: This is currently a work-in-progress build containing unfinished key-bindings and configuration.

## Features
- custom rendering of lines/blocks/braille character for gap-less alignment
- terminal opacity
- dark theme styling
- auto-hide cursor on keystrokes and show on mouse movement
- open new terminal with current terminal directory
- keyboard and mouse scrolling

## Requirements
- Xlib header files
- a composite manager (e.g. picom)
- [Hack] font (unless changed in the configuration file)

## Patches
- [boxdraw]
- [alpha]
- [gruvbox]
- [hidecursor]
- [newterm]
- [scrollback]

## Installation
Ensure you have the requirements, then clone the repository and run `sudo make clean install`.

## Credits
The [suckless] team and contributors.

[//]: Links
[suckless]: https://www.suckless.org
[st]: https://st.suckless.org
[boxdraw]: https://st.suckless.org/patches/boxdraw
[alpha]: https://st.suckless.org/patches/alpha
[gruvbox]: https://st.suckless.org/patches/gruvbox
[hidecursor]: https://st.suckless.org/patches/hidecursor
[clipboard]: https://st.suckless.org/patches/clipboard
[newterm]: https://st.suckless.org/patches/newterm
[scrollback]: https://st.suckless.org/patches/scrollback
[Hack]: https://github.com/source-foundry/Hack
