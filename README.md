## FFmpeg Static Builder OS X 64bits
#### Include Last Versions of x264 | x265 | AV1 | FFmpeg…

## Request :

##### =-> Mac OsX 10.10 < 10.13

## How Use :

##### =-> Download :
```
git clone https://github.com/albinoz/ffmpeg-static-OSX.git ~/Desktop/ffmpeg-static-OSX-master
```
##### =-> Make Executable :
```
chmod +x ~/Desktop/ffmpeg-static-OSX-master/ffmpeg-static-OSX.command
```

##### =-> Build :
```
~/Desktop/ffmpeg-static-OSX-master/ffmpeg-static-OSX.command
```
## Result :

##### =-> On Successfully Build :
`ffmpeg static binary be copied on Desktop`

##### x-> On Error Build :
`Please Report with log to`
https://github.com/albinoz/ffmpeg-static-OSX/issues

##### =-> Include :
```
./configure --extra-version=adam-`date +"%m-%d-%y"` --arch=x86_64 \
 --enable-hardcoded-tables --enable-pthreads --enable-postproc --enable-runtime-cpudetect \
 --pkg_config='pkg-config --static' --enable-nonfree --enable-gpl --enable-version3 --prefix=${TARGET} \
 --disable-ffplay --disable-ffprobe --disable-debug --disable-doc \
 --enable-libopus --enable-libvorbis --enable-libtheora --enable-libmp3lame --enable-libfdk-aac \
 --enable-libtwolame --enable-libopencore_amrwb --enable-libopencore_amrnb --enable-libgsm \
 --enable-libxvid --enable-libx264 --enable-libx265 --enable-libvpx --enable-libaom \
 --enable-avfilter --enable-filters --enable-libass --enable-fontconfig --enable-libfreetype \
 --enable-libbluray --enable-bzlib --enable-zlib \
 --enable-opengl --enable-opencl --enable-openal
```

