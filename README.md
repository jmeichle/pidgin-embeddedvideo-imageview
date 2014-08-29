# Version
------------------

Fork (currently unversioned) from on a [modified](#Modifications) copy of pidgin-embeddedvideo 1.2


# Modifications
------------------

This repo contains a copy of a modified version of pidgin-embeddedvideo plugin, imported via tarball from: http://geekr.googlecode.com/files/pidgin-embeddedvideo-imageview.tar.gz

This modified version includes basic rendering of images in chat windows as well as the underlying video support. More information can be found at http://code.google.com/p/pidgin-embeddedvideo/issues/detail?id=18


# Todos

- The image rendering does not scale to the chat window size
- No customization on supported websites and types of rendering (images).
 

Source Installation
------------------

Based on http://code.google.com/p/pidgin-embeddedvideo/wiki/InstallationGuide

You will need these packages to be installed before compiling the plugin on your machine:

pidgin-dev
libglib2.0-dev
libcurl3-dev
libwebkit-dev >= 1.1.12

On Ubuntu/Debian, dependancies can be installed via:

```
sudo apt-get install pidgin-dev libglib2.0-dev libcurl3-dev libwebkit-dev
```

then compile and install via:

```
./configure
make
make install
```

Restart Pidgin, activate Pidgin Embedded Video under the "Plugins"


Enjoy
------------------

**Free Software, Hell Yeah!**


------------------

# original README:

Find everything about this plugin on the project's site:
http://code.google.com/p/pidgin-embeddedvideo/
