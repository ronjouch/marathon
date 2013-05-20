marathon
========

**marathon** is a minimal bash/unix based launcher that tries to be smart about running or focusing apps. Just call `marathon SomeApplication`, and:

* if *SomeApplication* is not running, marathon will **run** it
* else marathon will just **focus** it

That way, after binding your favorite apps to a few easily-accessible keyboard shortcuts, you can access them with a single keypress and forget about alt-tab or clicking it in the dock / selector.

Installation
------------

1. Install `wmctrl`
2. Drop the script somewhere (e.g. `~/.scripts/marathon`) and link it to somewhere in your `$PATH`, e.g. `sudo ln -s ~/.scripts/marathon /usr/local/sbin/marathon`
3. Bind `marathon command` to some keyboard shortcut:
    * GNOME → System Settings → *Keyboard* section → *Shortcut* tab → *Custom Shortcuts*
    * LXDE → your `lxde-rc.xml`

Todo
----

* Proper handling of WM_CLASSES, currently it just assumes the class will contain the executable name. Works for all my apps though.
* (Maybe) use xdotool, it looks simpler
* (Maybe) if app runs and focused, then minimize it

License
-------

Licenced under the WTFPL, 2012-2013, [ronan@jouchet.fr](mailto:ronan@jouchet.fr)