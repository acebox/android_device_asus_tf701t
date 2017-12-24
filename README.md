# android_device_asus_tf701t

DISCLAIMER: Use at your own risk, this has worked fine for me however proceed with caution just in case; aka: Make sure you have full backups and the ability to use them.

This device tree is a copy of the one I used to build TWRP for the TF701T tablet.  It is based off the Zombi-X device tree with modded components from the KatKiss device tree.

MISC NOTES:
-Device tree was built under zombi-x (lp/5.1 branch)
-Local_manifest used to sync omni's 8.x twrp sources.
-Prebuilt kernel included, however inline building is completely possible now (make sure ramdisk reads LZMA).
-This prebuilt kernel supports F2FS and SELinux, it's built from the sources on my github repo.
-This tree should also build for "normal" android, however I've built up to 5.1 - so I cannot comment on newer builds (MM,N,etc..) - but give it a shot if you'd like.

That being said, download and compile to your hearts content!