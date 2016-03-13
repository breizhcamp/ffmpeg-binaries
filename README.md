# FFmeg static binaries

## OSX

Built from https://github.com/ydubreuil/FFmpeg/tree/avf2 to get proper screen capture on MacOSX

Command used:

    ./configure --cc=/usr/bin/clang --prefix=/opt/ffmpeg --as=yasm --extra-version=tessus --enable-avisynth --enable-fontconfig --enable-gpl --enable-libfreetype --enable-libmodplug --enable-libmp3lame --enable-libopus --enable-libschroedinger --enable-libsnappy --enable-libsoxr --enable-libvorbis --enable-libvpx --enable-libwavpack --enable-libx264 --enable-libxvid --enable-version3 --disable-ffplay --disable-indev=qtkit --disable-indev=x11grab_xcb

