# ffmpeg-rtmfp-small-binaries-portable-all-OS
Series of smallest ffmpeg 4.1 binaries compiled with rtmfp and major encoders/decoders
as static and portable for all major operating systems

- ffmpeg32L:      Linux 32bit
- ffmpeg64L:      Linux 64bit
- ffmpeg32W.exe:  Windows XP->10 32bit
- ffmpeg64W.exe:  Windows XP->10 64bit
- ffmpeg64M:      Mac OSX 10.x
On rails: IOS, Android

#### Compiled with the following options (other than Linux have the OS corresponding options)
ffmpeg version N-89993-g995e2c6-ffmpeg-windows-build-helpers Copyright (c) 2000-2018 the FFmpeg developers
built with gcc 5.4.0 (Ubuntu 5.4.0-6ubuntu1~16.04.4) 20160609
configuration: 
   --pkg-config=pkg-config --pkg-config-flags=--static --extra-version=ffmpeg-windows-build-helpers --enable-version3 
  --disable-debug --disable-w32threads --enable-zlib --enable-libv4l2 --enable-libxcb --enable-libxcb-shm --enable-libxcb-xfixes
  --enable-libxcb-shape --disable-autodetect --enable-librtmfp --enable-libmp3lame --extra-libs=-lm --extra-libs=-lpthread 
  --extra-cflags=-DLIBTWOLAME_STATIC --extra-cflags=-DMODPLUG_STATIC --extra-cflags=-DCACA_STATIC --enable-amf 
  --disable-libmfx --enable-gpl --enable-libx264 --enable-libx265 --enable-avresample --extra-cflags='-mtune=generic' 
  --extra-cflags=-O3 --enable-static --disable-shared 
  --prefix=/home/rdp/ffmpeg-windows-build-helpers/sandbox/cross_compilers/native
  libavutil      56.  7.100 / 56.  7.100
  libavcodec     58.  9.100 / 58.  9.100
  libavformat    58.  7.100 / 58.  7.100
  libavdevice    58.  0.101 / 58.  0.101
  libavfilter     7. 11.101 /  7. 11.101
  libavresample   4.  0.  0 /  4.  0.  0
  libswscale      5.  0.101 /  5.  0.101
  libswresample   3.  0.101 /  3.  0.101
  libpostproc    55.  0.100 / 55.  0.100

#### Big thanks to:

Roger Pack for all the nice work (Contact him if you need more options, donation welcome)
- https://sourceforge.net/projects/ffmpegwindowsbi/reviews
- http://rdp.inet2.org

Thomas Jammet who developed librtmfp (UDP encrypted protocol for web multicast and peer to peer, donation welcome)
- https://github.com/MonaSolutions/librtmfp
