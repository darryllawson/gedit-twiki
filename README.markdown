# gedit-twiki

This is a [GtkSourceView](http://projects.gnome.org/gtksourceview/) language
definition that enables syntax highlighting for TML markup, used by 
[TWiki](http://twiki.org/) and [Foswiki](http://foswiki.org/) in 
[gedit](http://projects.gnome.org/gedit/), the official GNOME text editor.


### Why is TML syntax highlighting useful?

TWiki&Foswiki have you editing pages in a HTML textarea or a web based WYSIWYG editor;
wouldn't you rather use a proper text editor like gedit? Once you are editing
TWiki pages with gedit, the next thing you'll want is syntax highlighting, for
benefits such as:

* Highlight headings, making document navigation easier.
* Highlight markup, making it easier to visualise formatting and detect syntax
  errors. For example, you'll know when you accidentally typed four spaces
  instead of the requisite three.
* Highlight wiki words; you'll know straight away if you have typed a valid =
  one, and it'll also be obvious when you need to escape one.

The [It's All Text!](https://addons.mozilla.org/en-US/firefox/addon/its-all-text/)
Firefox Add-on makes it easy to edit HTML textareas in your favourite editor.
See below for more information.

### Installation

Requires: gedit 2 (and GtkSourceView 2) or gedit 3 (and GtkSourceView 3).

Download the latest version of gedit-twiki from
https://github.com/darryllawson/gedit-twiki/downloads/, extract the zip
and copy twiki.lang into the language-specs directory:

* *Linux (gedit 2.x):* ~/.local/share/gtksourceview-2.0/language-specs/ <br>
(Create with "mkdir -p ..." if does not exist.)
* *Linux (gedit 3.x):* ~/.local/share/gtksourceview-3.0/language-specs/ <br>
(Create with "mkdir -p ..." if does not exist.)
* *Mac OS X:* /Applications/gedit.app/Contents/Resources/share/gtksourceview-2.0/language-specs/
* *Windows:* C:\Program Files\gedit\share\gtksourceview-2.0\language-specs\

Then close all gedit windows and restart. Select TWiki
highlighting from the View menu: View > Highlight Mode > Markup > TWiki.


### Configuring the It's All Text! Firefox Plugin

Install the [It's All Text!](https://addons.mozilla.org/en-US/firefox/addon/its-all-text/)
Firefox Add-on, and configure its preferences from
*Tools > It's All Text! > Preferences...*:

* *Editor (Linux)*: /usr/bin/gedit
* *Editor (Mac OS X)*: /Applications/gedit.app
* *File Extensions*: ﻿.twiki,.txt,.html,.css,.xml,.xsl,.js <br>
(.twiki appearing first makes it the default.)
* *Hot Key (Linux)*: ctrl E
* *Hot Key (Max OS X)*: meta E (meta is the command key)

The *Hot Key* and *File Extensions* settings above are of course just
recommendations.

To try it out, edit a random TWiki page at
http://twiki.org/cgi-bin/edit/Sandbox/RandomTestTopic937. Logon with the
guest account (Username: TWikiGuest, Password: guest). Click the pick shaped
icon ("Edit TWiki Markup") on the toolbar, click the blue Edit button (usually
at the bottom right) and gedit should pop up in TWiki editing mode.

*Tip:* Right click on the blue Edit button for a menu of "Edit as" items and
"Edit with new extension...".


### Contributing

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
