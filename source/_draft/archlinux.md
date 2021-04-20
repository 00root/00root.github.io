---
title: arch linux
date: 2021-02-24 20:39:06
tags: 
  - Linux
# demenu does not browse $PATH
1. Place env vars in ~/.profile or ~/.xprofile (Create if doesn't exist), not in ~/.bashrc
2. rm -f ~/.cache/dmenu_run
3. Log out and log in

To debug env vars type:

1. In dmenu: echo $PATH > /tmp/path
2. In terminal: cat /tmp/path

