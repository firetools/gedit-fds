# Syntax highlighting for Linux Gnome FDS editors

If you are using NIST FDS on Linux, and you are editing your cases
with the new [Gnome Text Editor](https://flathub.org/apps/org.gnome.TextEditor),
you can install this specific syntax highlighting.

## How to install

- Download the latest version of the [fds.lang](https://raw.githubusercontent.com/firetools/gedit-fds/main/fds.lang) file.
- Copy the `fds.lang` file to one of the following locations, depending on how your editor was installed:
  - current [flatpak version](https://flathub.org/apps/org.gnome.TextEditor): `~/.var/app/org.gnome.TextEditor/data/libgedit-gtksourceview-300/language-specs/`;
  - current packaged version (eg. rpm, deb): `~/.local/share/libgedit-gtksourceview-300/language-specs/`;
  - olders versions: `~/.local/share/gtksourceview-5/language-specs/`.

Restart your session and enjoy FDS syntax highlighting in the [Gnome Text Editor](https://flathub.org/apps/org.gnome.TextEditor).

### License

This plugin is released under the GNU General Public License (GPL) 2016 by Emanuele Gissi, PhD.

![](https://github.com/firetools/blenderfds/wiki/p/fds-gedit.png)
