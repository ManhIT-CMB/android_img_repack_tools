android_img_repack_tools
====================

android_img_repack_tools is a kit utilites for unpack/repack android ext4 and boot images

how to make:

$ sudo apt-get install git-core gnupg flex bison gperf libsdl-dev libesd0-dev build-essential zip curl libncurses5-dev zlib1g-dev valgrind libreadline6-dev gcc-multilib g++-multilib libc6-dev x11proto-core-dev libx11-dev libz-dev gawk texinfo automake libtool cvs libsdl-dev gcc-5

$ ./configure

$ make

will compille binaries:
mkbootfs
simg2simg
make_ext4fs
mkbootimg
sgs4ext4fs
unpackbootimg
ext2simg
img2simg
simg2img
append2simg

$ make clean

will clean sources

$ make clear

will remove sources

