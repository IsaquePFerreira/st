# My fork and buil of st - simple terminal
My customization of st with some patches and keys for my
daily use

Keybinds
---
- Zoom+ - ControlMask+ShiftMask+plus
- Zoom- - ControlMask+minus
- Zoom reset - ControlMask+equal
- Scroll Up - ShiftMask+Page_Up
- Scroll Dowm - ShiftMask+Page_Down

Patches
---
- Alpha
- Any Size
- ScrollBack RingBuffer
- Vert Center

Requirements
---
For Void Linux:
```sh
sudo xbps-install -S base-devel libX11-devel libXft-devel libXinerama-devel noto-fonts-ttf noto-fonts-ttf-extra font-hack-ttf
```
Installation
---
```sh
git clone https://github.com/IsaquePFerreira/st
cd st
make
sudo make clean install
```
