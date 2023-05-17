# GTK syntax highlighting for NIST FDS input files

[GTK](https://www.gtk.org/) is the cross-platform development tool for the Linux GNOME desktop environment.
GNOME text editors (eg. Gnome GEdit and [Text Editor](https://gitlab.gnome.org/GNOME/gnome-text-editor)) use GTK syntax highlighting.

Released under the terms of the GNU General Public License, GTK, GEdit, and Text Editor are free software.

## How to install

- Download the latest version of the [fds.lang](https://raw.githubusercontent.com/firetools/gedit-fds/main/fds.lang) file
- In Linux, copy the `fds.lang` file to the following locations:
   * `~/.local/share/gtksourceview-4/language-specs/`
   * `~/.local/share/gtksourceview-5/language-specs/`, for Gnome 42 or later
   or run the following commands in a terminal window:
   ```bash
   mkdir -p ~/.local/share/gtksourceview-{4..5}/language-specs
   cp -n fds.lang ~/.local/share/gtksourceview-4/language-specs
   cp -n fds.lang ~/.local/share/gtksourceview-5/language-specs
   ```
- Run the `GEdit` editor or the new `Text Editor` and enjoy FDS syntax highlighting.

### License

This plugin is released under the GNU General Public License (GPL) 2016 by Emanuele Gissi, PhD.

![](https://github.com/firetools/blenderfds/wiki/p/fds-gedit.png)
