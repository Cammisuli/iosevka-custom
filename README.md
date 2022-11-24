# IOSEVKA Customized

My settings for building the iosevka font

## Build using docker

A Docker container handling the build environment for you can be found [here](https://github.com/avivace/fonts-iosevka).

Then run this command:

```
docker run -e FONT_VERSION=16.4.0 -it -v (pwd):/build avivace/iosevka-build ttf::iosevka-custom
```

## Nerd Fonts

```
fontforge -script ./FontPatcher/font-patcher dist/iosevka-custom/ttf/iosevka-custom-regular.ttf -s -l -c
```
