# Android device tree for samsung SM-A057G (a05s)

# Clone
    git clone https://github.com/TheNoobDevs/android_device_samsung_a05s -b twrp-12.1 device/samsung/a05s

# Build twrp
    ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_a05s-eng; mka recoveryimage

# WARNING!!!
UNLOCKING YOUR BOOTLOADER WILL VOID YOUR WARRENTY!