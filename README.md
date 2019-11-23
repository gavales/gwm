# gwm

## Demo

[gwmdemo](gwmdemo.gif)

## Description

Window manager using `cwm` + and scripts that utilise `wmutils`.  
Based on Michael Misch's [hwwm](https://github.com/halfwit/hwwm) which I saw in
[this video](https://www.youtube.com/watch?v=MSIjqTgtj2c), but made from scratch
and changed up a bit.

## Dependencies

`cwm`  
until I can use plain Xorg

`wmutils`  
not git version, cos that `wew` doesn't register `CREATE` events on my computer

`mmutils`  
In case I use multiple monitors

## Install

```bash
$ cd ~/.config
~/.config $ git clone https://github.com/StillANixRookie/gwm.git
~/.config $ echo "export PATH=$PATH:$HOME/.config/gwm/bin" >> ~/.bash_profile
~/.config $ # OR: echo "export PATH=$PATH:$HOME/.config/gwm/bin" >> ~/.profile
```

