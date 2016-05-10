Keyboard remapping in Ubuntu
============================

# Background

I am using a Microsoft Natural Ergonomic 4000 keyboard on a MacBook Pro laptop and running Ubuntu in Virtualbox.

_This may be useful for Emacs users._

**The file swaps CAPS with Left CTRL and enables the Right ALT key (meta).**

## Install
Copy file to `/usr/share/X11/xkb/symbols/pc`.

```shell
  sudo cp pc /usr/share/X11/xkb/symbols/pc
```

Restart the machine.
