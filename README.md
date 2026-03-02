Prepared for Ubuntu 24.04 LTS - wlroots 0.17.1 

[https://gitlab.freedesktop.org/wlroots/wlroots/-/releases/0.17.1](https://gitlab.freedesktop.org/wlroots/wlroots/-/releases/0.17.1)

---
>#> wayland-scanner server-header \
>    /usr/share/wayland-protocols/stable/xdg-shell/xdg-shell.xml \
>    xdg-shell-protocol.h

>#> meson setup build
>#> ninja -C build