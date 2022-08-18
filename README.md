# IOSEVKA Customized

My settings for building the iosevka font

## Build using docker

A Docker container handling the build environment for you can be found [here](https://github.com/avivace/fonts-iosevka).

Then run this command:

```
docker run -e FONT_VERSION=15.3.1 -it -v (pwd):/build avivace/iosevka-build ttf::iosevka-custom
```
