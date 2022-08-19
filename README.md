# GEdit syntax highlighting for NIST FDS input files

[GEdit](https://wiki.gnome.org/Apps/Gedit) is a text editor for the Linux GNOME desktop environment. It is available on Mac OS X and Microsoft Windows as well.

Designed as a general purpose text editor, gedit emphasizes simplicity and ease of use. It includes tools for editing source code and structured text such as markup languages. It is designed to have a clean, simple graphical user interface according to the philosophy of the GNOME project, and it is the default text editor for GNOME.

Released under the terms of the GNU General Public License, GEdit is free software.

## How to install

- Download the latest version of the [fds.lang](https://raw.githubusercontent.com/firetools/gedit-fds/main/fds.lang) file
- In Linux, copy the `fds.lang` file to the following locations:
   * `~/.local/share/gtksourceview-3.0/language-specs/`, for old Gnome versions
   * `~/.local/share/gtksourceview-4/language-specs/`
   * `~/.local/share/gtksourceview-5/language-specs/`, for Gnome 42 or later
   or run the following commands in a terminal window:
   ```bash
   mkdir -p ~/.local/share/gtksourceview-{3..4}.0/language-specs
   cp -n fds.lang ~/.local/share/gtksourceview-3.0/language-specs
   cp -n fds.lang ~/.local/share/gtksourceview-4/language-specs
   cp -n fds.lang ~/.local/share/gtksourceview-5/language-specs
   ```
- Run the `gedit` editor or the new `gnome-text-editor` and enjoy FDS syntax highlighting.

### License

This plugin is released under the GNU General Public License (GPL) 2016 by Emanuele Gissi, PhD.

![](https://github.com/firetools/blenderfds/wiki/p/fds-gedit.png)
