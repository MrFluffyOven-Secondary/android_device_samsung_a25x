# Android device tree for samsung SM-A256U1 (a25x)

# Clone
    git clone https://github.com/TheNoobDevs/android_device_samsung_a25x -b twrp-12.1 device/samsung/a25x

# Build twrp
    ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_a25x-eng; mka recoveryimage

# WARNING!!!
UNLOCKING YOUR BOOTLOADER WILL VOID YOUR WARRENTY!
