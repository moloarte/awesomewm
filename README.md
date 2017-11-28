# awesomewm
awesome windows manager tool configuration

awesome --version

```bash
awesome v4.0 (Harder, Better, Faster, Stronger)
 • Compiled against Lua 5.1.5 (running with Lua 5.1)
 • D-Bus support: ✔
 • execinfo support: ✔
 • RandR 1.5 support: ✘
 • LGI version: 0.9.1
```

standard awesome with:

* brightness widget
* cpu-widget
* volume and volumebar widget
* weather widget
* batteryarc widget

## Requirements

1. https://github.com/streetturtle/awesome-wm-widgets
1. https://github.com/horst3180/arc-icon-theme#installation
1. lua-socket package 

## Additional Controls

* Super + Control L : xscreensaver-command -lock

## Test your configuration

I use the follow commands to test my configuration before reloading

1. Xephyr  :1 -ac -br -noreset -screen 1152x720 &
1. DISPLAY=:1.0 awesome -c ~/.config/awesome/rc.lua 