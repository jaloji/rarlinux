# RAR binaries for linux x86/64

Requirements
------------
You will need some libs to run some x86:
```
dpkg --add-architecture i386
apt-get install libc6-i386 libstdc++5 libstdc++5:i386 lib32stdc++6 lib32z1 lib32ncurses6
wget http://archive.debian.org/debian/pool/main/g/gcc-2.95/libstdc++2.10-glibc2.2_2.95.4-27_i386.deb
dpkg -i libstdc++2.10-glibc2.2_2.95.4-27_i386.deb
```

All versions before < 2.71 crashes, so I removed them.
Version 7 is useless and crashes, so removed too.
