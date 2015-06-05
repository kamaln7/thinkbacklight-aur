# thinkbacklight-aur

An AUR package for [https://gist.github.com/hadess/6847281](https://gist.github.com/hadess/6847281). Thanks @hadess.

## Dependencies

* core/glibc >= 2.0.0
* core/pkg-config

The dependencies should be automatically installed by `makepkg` as long as the `-s` option is passed.

## Installation

Use your favorite pacman helper to install the AUR package `thinkbacklight` or build it yourself:

```
git clone https://github.com/kamaln7/thinkbacklight-aur.git
cd thinkbacklight-aur
makepkg -s -c
sudo pacman -U *.tar.xz
```

## Usage

```
sudo thinkbacklight <level>
```

### Levels

1. Medium Brightness
2. Full Brightness
3. Off
