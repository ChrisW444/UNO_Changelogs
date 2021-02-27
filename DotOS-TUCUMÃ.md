# DotOS 5.0-TUCUMÃ
# 27-02-2021

#Changes
- switch to enforcing
- removed Safailnet
- Reduce screenshot delay to 0
- Disable foreground prefer_idle & reduce TA boost
- Removed all prebuilts apps
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
