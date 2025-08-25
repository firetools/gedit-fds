# Syntax highlighting for NIST FDS input files in Linux text editors 

If you are using NIST FDS on Linux, and you are editing your cases
with the new [Gnome Text Editor](https://gitlab.gnome.org/GNOME/gnome-text-editor),
you can install a specific syntax highlighting.

## How to install

- Download the latest version of the [fds.lang](https://raw.githubusercontent.com/firetools/gedit-fds/main/fds.lang) file.
- Copy the `fds.lang` file to the following locations:
  - `~/.local/share/gtksourceview-5/language-specs/`, for olders versions;
  - `~/.local/share/libgedit-gtksourceview-300/language-specs/`, for the packaged version (eg. rpm, deb);
  - `~/.var/app/org.gnome.TextEditor/data/libgedit-gtksourceview-300/language-specs/`, for the [flatpak version](https://flatpak.org/).

Restart your session and enjoy FDS syntax highlighting in Gnome Text Editor

### License

This plugin is released under the GNU General Public License (GPL) 2016 by Emanuele Gissi, PhD.

![](https://github.com/firetools/blenderfds/wiki/p/fds-gedit.png)
