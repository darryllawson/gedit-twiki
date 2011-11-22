This is a [GtkSourceView](http://projects.gnome.org/gtksourceview/) language
definition that enables syntax highlighting for [TWiki](http://twiki.org/)
markup in [gedit](http://projects.gnome.org/gedit/), the official GNOME text
editor.

### Installation

Requires: gedit 2 (and GtkSourceView 2) or gedit 3 (and GtkSourceView 3).

Download the latest version of gedit-twiki from
https://github.com/darryllawson/gedit-twiki/downloads/, extract the zip contents,
and copy twiki.lang into the language-specs directory:

* *Linux (gedit 2.x):* `~/.local/share/gtksourceview-2.0/language-specs/`
  (create with "mkdir -p ..." if does not exist)
* *Linux (gedit 3.x):* `~/.local/share/gtksourceview-3.0/language-specs/`
  (create with "mkdir -p ..." if does not exist)
* *Mac OS X:* `/Applications/gedit.app/Contents/Resources/share/gtksourceview-2.0/language-specs/`
* *Windows:* `C:\Program Files\gedit\share\gtksourceview-2.0\language-specs\`

Then close all gedit windows and restart. Select TWiki
highlighting from the View menu: View > Highlight Mode > Markup > TWiki.


### Why is TWiki syntax highlighting useful?

TWiki has you editing pages in a HTML textarea, which is a pain; wouldn't you
rather use a proper text editor like gedit? The
[It's All Text!](https://addons.mozilla.org/en-US/firefox/addon/its-all-text/)
Firefox plugin (or similar) makes it easy to edit HTML textareas in your
favourite editor. Once you are editing TWiki pages with gedit, the next thing
you'll want is syntax highlighting, for these benefits:

* Highlight headings, making it easy to navigate the document.
* Highlight keywords and markup elements, making it easy to visualise
  formatting and detect syntax errors. For example, you'll know when you
  accidentally typed four spaces instead of the requisite three.
* Highlight wiki words; useful in making sure you have typed a valid one, and
  to inform you when you should escape one (using a ! prefix).


### Development

This project is hosted at https://github.com/darryllawson/gedit-twiki/.
Report issues at https://github.com/darryllawson/gedit-twiki/issues/
and see https://github.com/darryllawson/gedit-twiki/wiki/ for more
development information.


### License

Copyright (C) 2011 Darryl Lawson &lt;darryl.lawson@me.com&gt;

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
