# m21-android-experiments

## Experiments
1. Booted Android 13 Pixel Experience GSI with GApps

>Worked better than expected

>Volte bugs

2. Booted Android 16 (QPR2) crDroid 12.8 ROM, no GApps [Official build]

>Auto-brightness has slight bugs

>Smoother than OneUI

3. Booted Android 16 (QPR2) LineageOS 23.2 ROM, no GApps [Unofficial build]

>Smoother than crDroid

>However, less customisation than other builds

## Discoveries

1. Bootloop bypass due to broken security HALs

>A method involving rapid navigation gesture input (spamming) on the home pill/home button on 2-button/3-button navigation bars during rebooting of a GSI. Forces the system to respond and go to the home page before other security measures kick in. Works only if rapidly giving navigation gesture inputs (spamming) the moment the navigation bar appears. Used for devices with incomplete Treble support, especially Exynos devices.
