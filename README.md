
Execute this shell command.

```
#!/bin/sh
gsettings set org.gnome.settings-daemon.plugins.keyboard active false
kbcomp -I$USER/.xkb $USER/.xkb/keymap/mykbd :0
```
