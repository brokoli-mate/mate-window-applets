# mate-window-applets
Applets for mate-panel to show window controls.

WindowButtons applet will show you close,minimize,actions .

WindowLabel applet will show you the class,title,role,xid,pid of active window .

WindowMenu applet will show you the window menu of the active window.

   #### This is not my project and i'm not a coder. I've just uploaded an existing version of closed project so anybody can download it. I have also add some custom themes for window buttons applet.

### License

> GPLv3

Also see LICENSE file.
 
### How to install

#### Requerments

##### For install

meson,
ninja,
vala,

Gtk3,
Gdk3,
libwnck3

#### Install

> meson --prefix=/usr build

> cd build

> ninja

> sudo ninja install

>sudo ./install-icons.sh install

>sudo glib-compile-schemas /usr/share/glib-2.0/schemas

#### Uninstall

> sudo ninja uninstall

>sudo ./install-icons.sh uninstall
