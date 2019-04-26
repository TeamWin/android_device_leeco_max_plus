TWRP device configuration for LeEco Le Max Pro
==============

kernel source used for prebuilt kernel:
https://github.com/LineageOS/android_kernel_leeco_msm8996/

To compile android-9.0 based TWRP
==============

    export ALLOW_MISSING_DEPENDENCIES=true
    . build/envsetup.sh
    lunch omni_max_plus-eng && \
    mka adbd recoveryimage 2>&1 | tee make_max_plus.log

tee command makes a copy of the terminal output to a file.
If you're using Windows PowerShell? Please relace tee with
Tee-Object


Device configuration for Letv Le Max Pro (x910)
=====================================

|Basic                    | Spec Sheet                                                                  |
|------------------------:|:----------------------------------------------------------------------------|
| CPU                     | Dual-core 2.15GHz Kryo & dual-core 1.6GHz Kryo                              |
| CHIPSET                 | Qualcomm MSM8996 Snapdragon 820                                             |
| GPU                     | 624MHz Adreno 530                                                           |
| Memory                  | 4/6 GB (LPDDR4 1866MHz dual-channel)                                        |
| Shipped Android Version | 6.0 (Marshmallow)                                                           |
| Storage                 | 32/64/128 GB (UFS2.0)                                                       |
| Battery                 | 3400 mAh (non-removable)                                                    |
| Dimensions              | 169.1 x 83.5 x 8.9 mm                                                       |
| Display                 | 1440 x 2560 pixels, 6.33" LTPS IPS LCD, 16:9 ratio (~464 PPI density)       |
| Rear Camera             | 21.0 MP, LED flash (Sony Exmor RS IMX230 f/2.0, 1/2.4")                     |
| Front Camera            | 4.1 MP (OmniVision OV4688 f/2.0 1/3")                                       |
| Extra Features          | 60Ghz Wi-Fi AD, Hi-Fi Audio DAC (ES9018), IR Blaster (MAXQ616), NFC (PN548) |
| Release Month           | May 2016                                                                    |

<p align="center">
<img height="600" src="https://i.imgur.com/cPCQz0g.png" title="LeEco Le Max Pro">
</p>
