This is a [GtkSourceView](http://projects.gnome.org/gtksourceview/) language definition that
enables syntax highlighting for [TWiki](http://twiki.org/) markup in [gedit](http://projects.gnome.org/gedit/),
the official GNOME text editor.

Why is TWiki syntax highlighting useful?
----------------------------------------

TWiki has you editing pages in a HTML textarea, which is a pain; wouldn't you rather use a proper
text editor like gedit? The [It's All Text!](https://addons.mozilla.org/en-US/firefox/addon/its-all-text/)
Firefox plugin (or similar) makes it easy to edit HTML textareas in your favourite editor.
Once you are editing TWiki pages with gedit, the next thing you'll want is syntax highlighting, for these benefits:

* Highlight headings, making it easy to navigate the document.
* Highlight keywords and markup elements, making it easy to visualise formatting and detect syntax erros.
  For example, you'll know when you accidentally typed four spaces instead of the requisite three.
* Highlight wiki words; useful in making sure you have typed a valid one, and to inform you when
you should escape one (using a ! prefix), in case you don't want auto-linking.

Installation
------------

Simply copy `twiki.lang` into the `language-specs` directory:

* *Linux:* `~/.local/share/gtksourceview-2.0/language-specs/`
* *Mac OS X:* `/Applications/gedit.app/Contents/Resources/share/gtksourceview-2.0/language-specs/`
* *Windows:* `C:\Program Files\gedit\share\gtksourceview-2.0\language-specs\`

Close all gedit windows and then restart gedit.

Development
-----------

This project is hosted at [https://github.com/darryllawson/gedit-twiki/](https://github.com/darryllawson/gedit-twiki/]).

Grab a git clone like this:

    $ git clone git://github.com/darryllawson/gedit-twiki.git

See https://github.com/darryllawson/gedit-twiki/wiki for more development information.

License
-------

Copyright (C) 2011 Darryl Lawson (darryl.lawson@me.com)

This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Library General Public
License as published by the Free Software Foundation; either
version 2 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Library General Public License for more details.

You should have received a copy of the GNU Library General Public
License along with this library; if not see
http://www.gnu.org/licenses/.
