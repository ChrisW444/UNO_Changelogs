# DotOS for Redmi Note 7/7s
# Version: 5.0 - 10-03-2021
# Kernel 4.19

#Changes
- Add Gboard in Vanilla Builds
- Add init changes required for power-libperfmgr
- Drop zram
- Enable fluence voice recording
- Import pixel power hidl
- Improve ram management
- Introduce 'SafailNet'
- rootdir: configure some post_boot values from wahoo
- Update: rootdir from LA.UM.9.2.1.r1-06000-sdm660.0
- Update: Kang some post-boot values from bengal
- Update vendor SPL from LA.UM.8.2.r1-07400-sdm660.0
- Update: qti-telephony-common from nubia
- pdate fingerprint to Redfin - RQ2A.210305.006
- Set Netflix property based on target

# Fix
- Fix Ok Google.
- Standard camera replaced by GcamGo 1.11. (old standard camera was crashing)
- Drop Spectrum from xiaomiparts. (this was getting in the way of performance and battery)

# 27-02-2021

#Changes
- switch to enforcing
- Removed Safailnet
- Removed all prebuilts apps
- Removed Gvisual Mod
- Reduce screenshot delay to 0
- Disable foreground prefer_idle & reduce TA boost
- enable f2fs support for data partitions
- Update wfd blobs from LA.UM.9.6.2.r1-03300-89xx.0
- Kang more pixel power HAL sepolicy


Fix: 
- fix green video recording through the camera
- fix hotspost didn't work for some people

# Dirac
- Add bass booster preset for MiSound (much stronger bass for those who use headphones)
- Add Blobs Dirac (adde some libs on vendor)
- Import MIUI dirac translations
- Fix: Dirac: Enable by default (dirac didn't work well at times)

# XiaomiParts
- Adding a few more props needed to work well in enforcing
- Adding XiaomiParts into the whitelist ( Adding XiaomiParts into whitelist to avoid it being killed by doze. Also granting necessary permission to function properly.Required for Headphone & Mic Gain as it currently get killed)
- Improvement Spectrum (cpu and gpu values adjusted for lavender)
- Specrtum adapted for EAS
- Update Icons
- FPS Info: redesign FPS Info (now it's better than ever hehe)
- Fix: Remove intent for BootReceiver
- Fix: Fix icon does not appear in white theme
- Fix: Removed all garbage that was not working

# Credits
- Thanks @NotZeetaa for kernel!
- Thanks @Golpiista, @inferno964 for tests!
