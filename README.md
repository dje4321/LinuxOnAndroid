# LinuxOnAndroid
Native Linux running on android without chroot

This project aims to attempt to integrate standard linux into android as much as possible. Has full support for glibc and all glibc apps including gdb, gcc, xorg, etc. It does this by using the fact that android isolates its linux system into /system. This allows you to plop down a standard linux system on the root directory withouth any of that stupid chroot nonsense. It is possible to integrate linux much more deeply by modifing /init.rc to automate all of this for you but that is beyond the scope of this right now. 
