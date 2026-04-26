### ffmpeg-wiiu

#### Instructions:
* Make sure you have exported $DEVKITPRO, $DEVKITPPC and $WUT_ROOT vars
* Clone the latest ffmpeg (https://github.com/FFmpeg/FFmpeg) or (https://github.com/FFmpeg/FFmpeg/commit/162ad61486a870691e9d992bdb17ea337fc16980)
* Copy the configure script (configure-wiiu) inside repo's root
* `ln -s /opt/devkitpro/portlibs/wiiu/bin/powerpc-eabi-pkg-config /opt/devkitpro/devkitPPC/bin/powerpc-eabi-pkg-config`
* `./configure-wiiu`

* `make install`
