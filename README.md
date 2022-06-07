# wofi-symbol

Simple symbol selector for Wayland using [wofi](https://cloudninja.pw/docs/wofi.html).
It relies on [wtype](https://github.com/atx/wtype) when it's supported, otherwise,
[wl-clipboard](https://github.com/bugaevc/wl-clipboard) is used instead.
(forked from [wofi-emoji](https://github.com/dln/wofi-emoji))

## Usage with Sway

Download [wofi-symbol](https://github.com/mijoharas/wofi-symbol/raw/master/wofi-symbol), ensure it's executable and somewhere in your `$PATH`.

Add a shortcut key in your [sway](https://swaywm.org/) config:

```
# ~/.config/sway/config

bindsym Mod4+e exec path/to/wofi-emoji
```
