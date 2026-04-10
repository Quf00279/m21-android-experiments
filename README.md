# Galaxy M21 Android Experiments

Device: Samsung Galaxy M21 (Exynos 9611)

---

## Experiments

### Android 13 - PixelOS GSI (with GApps)
- Boot: Yes
- Performance: Better than expected
- Issues:
  - VoLTE bugs

---

### Android 16 (QPR2) - crDroid 12.8 (Official, no GApps)
- Boot: Yes
- Performance: Smoother than OneUI
- Issues:
  - Slight auto-brightness bugs

---

### Android 16 (QPR2) - LineageOS 23.2 (Unofficial, no GApps)
- Boot: Yes
- Performance: Smoother than crDroid
- Notes:
  - Less customization compared to other builds
  - During flashing, DO NOT WIPE DALVIK/CACHE. IT CAUSES BOOTLOOPS.

---

## Discoveries

### Home Pill Hammer (Bootloop bypass for broken security HALs)

A method to bypass certain bootloops caused by broken or incomplete security HAL implementations.

#### Method:
- During boot, **spam navigation inputs** (home button / gesture pill)
- Timing is critical:
  - Start immediately when the navigation bar appears
- This can force the system to reach the home screen before security checks fully initialize

#### Works on:
- Some GSIs
- Devices with incomplete Treble support
- Especially Exynos-based devices

#### Note:
Experimental. Results may vary depending on ROM and device state

## ROM Sources

- PixelOS GSI (Android 13)

  Source: (https://github.com/MisterZtr/PixelOS_gsi/releases)

- crDroid 12.8 (Android 16, Official)

  Source: <link here>

- LineageOS 23.2 (Android 16, Unofficial)

  Source: <link here>
