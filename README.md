android_img_repack_tools
====================

android_img_repack_tools is a kit utilites for unpack/repack android ext4 and boot images

how to make:

$ ./configure

will download source from android git repositories

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
minigzip
pxa1088-mkbootimg
pxa1088-unpackbootimg
pxa1088-dtbTool

$ make clean

will clean sources

$ make clear

will remove sources

minigzip and mkimage are compiled in configure stage

