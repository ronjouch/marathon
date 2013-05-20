Licenced under the WTFPL, 2012, ronan@jouchet.fr
marathon tries to be smart about running or focusing apps
if "app" isn't running, "marathon app" runs "app", else it just focuses "app"

INSTALLATION
0. Install wmctrl
1. Put marathon somewhere accessible system-wide,
   e.g. sudo ln -s ./marathon /bin/marathon
2. Bind "marathon command" to some keyboard shortcut:
   GNOME -> the "Keyboard" applet of the GNOME System Settings
   LXDE -> your lxde-rc.xml

TODO
- Proper handling of WM_CLASSES, currently it just assumes the class will
  contain the executable name. Works for all my apps though.
- If app runs and focused, then minimize it
- Use xdotool, looks simpler but couldn't get my way around WM_CLASSES
