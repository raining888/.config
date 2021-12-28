# config

#### Introduction

This is my dot file.

##### Ranger

Install `ueberzug` for picture preview

Install `atool` for compress and extract_here

##### Input Methods

Install `fcitx` `fcitx-im` `fcitx-googlepinyin` `fcitx-configtool`

And in `/etc/X11/xinit/xinitrc`:

```
export GTK_IM_MODULE=fcitx
export QT_IM_MODULE=fcitx
export XMODIFIERS="@im=fcitx"
```

##### Fonts

In `locale.conf`

```
LANG=en_US.UTF-8
LC_ADDRESS=en_US.UTF-8
LC_IDENTIFICATION=en_US.UTF-8
LC_MEASUREMENT=en_US.UTF-8
LC_MONETARY=en_US.UTF-8
LC_NAME=en_US.UTF-8
LC_NUMERIC=en_US.UTF-8
LC_PAPER=en_US.UTF-8
LC_TELEPHONE=en_US.UTF-8
LC_TIME=en_US.UTF-8
```

Install `Source Code Pro` and `Noto`, and check `/usr/share/fonts/noto`

emoji:

```
ttf-linux-libertine
ttf-inconsolata
ttf-joypixels
noto-fonts-emoji
ttf-liberation ttf-droid
```

Chinses:

```
wqy-bitmapfont
wqy-microhei
wqy-microhei-lite
wqy-zenhei
adobe-source-han-mono-cn-fonts
adobe-source-han-sans-cn-fonts
adobe-source-han-serif-cn-fonts
```
