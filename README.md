TWRP device configuration for LeEco Le Max Pro
==============

kernel source used for prebuilt kernel:
https://github.com/LineageOS/android_kernel_leeco_msm8996/


To compile android-8.1 based TWRP
==============

export ALLOW_MISSING_DEPENDENCIES=true

. build/envsetup.sh && lunch omni_max_plus-eng

mka adbd recoveryimage
