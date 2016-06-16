Switch Document Plugin for Geany
=========================

About
-----------

Switch Document is a plugin for Geany that provides a dialog for rapid switching to any open document.


Building and Installing
-----------------------

Download the plugin from https://github.com/leifmariposa/geany-switch-document-plugin

Then run the following commands:

```bash
$ make
$ sudo make install
```

Using the Plugin
----------------

After having enabled the plugin inside Geany through Geany's plugin manager,
you'll need to setup a keybinding for triggering the Switch Document dialog. Go to
the preferences, and under the Keybindings tab set the Switch Document keybinding. 

Using the plugin is simple. Press the keybinding that you selected and the dialog will be shown.
Start typing any part of the filename of the document you want, if the desired document is first in 
the list (at the top) you can just press enter to activete it, if not use arrow down until it is 
selected and then press enter to activate it.


![screenshot](https://github.com/leifmariposa/geany-switch-document-plugin/blob/master/screenshots/screenshot.png?raw=true)

License
----------------

This plugin is distributed under the terms of the GNU General Public License
as published by the Free Software Foundation, either version 2 of the
License, or (at your option) any later version. You should have received a copy
of the GNU General Public License along with this plugin.  If not, see
<http://www.gnu.org/licenses/>. 

Contact
----------------

You can email me at &lt;leifmariposa(at)hotmail(dot)com&gt;
 
 
Bug reports and feature requests
----------------

To report a bug or ask for a new feature, please use the tracker
on GitHub: https://github.com/leifmariposa/geany-switch-document-plugin/issues
