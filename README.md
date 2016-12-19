# How-to-compile-X264-for-ARM

1-
```javascript
git clone git://git.videolan.org/x264.git
```

2-
```javascript
cd x264
```

3-
```javascript
./configure --cross-prefix=$TOOLCHAIN/bin/arm-linux-androideabi- --sysroot="$NDK_SYSROOT" --host=arm-linux --enable-pic --enable-static
```

Note: 

```javascript
$TOOLCHAIN = /home/drjacky/Desktop/DLz/android-ndk-r10e/toolchains/arm-linux-androideabi-4.8/prebuilt/linux-x86_64
$NDK_SYSROOT = /home/drjacky/Desktop/DLz/android-ndk-r10e/platforms/android-14/arch-arm
```
