<p align="center">
  <img src="https://raw.githubusercontent.com/BlackMesa123/KnoxPatch/main/readme-res/kp-readme-header.png" width="75%"/>
  <br>
  <a href="https://apt.izzysoft.de/fdroid/index/apk/io.mesalabs.knoxpatch"><img loading="lazy" src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png" width="170"/></a>
  <br>
  <a href="https://github.com/BlackMesa123/KnoxPatch/releases/latest"><img src="https://img.shields.io/github/v/release/Xposed-Modules-Repo/io.mesalabs.knoxpatch?display_name=release&style=for-the-badge"/></a>
  <a href="https://tooomm.github.io/github-release-stats/?username=Xposed-Modules-Repo&repository=io.mesalabs.knoxpatch"><img src="https://img.shields.io/github/downloads/Xposed-Modules-Repo/io.mesalabs.knoxpatch/total?style=for-the-badge"/></a>
  <a href="https://github.com/BlackMesa123/KnoxPatch"><img src="https://img.shields.io/badge/GitHub-Repo-lightgrey.svg?style=for-the-badge&logo=GitHub"/></a>
  <br><br>
  An <a href="https://github.com/LSPosed/LSPosed">LSPosed</a> module to get Samsung apps/features working again in your rooted Galaxy device.
  <br>
</p>

## Supported Android versions
- Android 9 (One UI 1.x)
- Android 10 (One UI 2.x)
- Android 11 (One UI 3.x)
- Android 12 (One UI 4.x)
- Android 12L (One UI 4.1.1)
- Android 13 (One UI 5.x)
- Android 14 (One UI 6.x)

## Supported apps
- ➖ [Galaxy Wearable (Gear Manager)](https://www.samsung.com/us/support/owners/app/galaxy-wearable-watch) ([Enhancer](#knoxpatch-enhancer) required)
- ✅ [Samsung Flow](https://www.samsung.com/uk/apps/samsung-flow/)
- ✅ [Samsung Health](https://www.samsung.com/uk/apps/samsung-health/)
- ✅ [Samsung Health Monitor](https://www.samsung.com/uk/apps/samsung-health-monitor/)
- ✅ [Secure Folder](https://www.samsungknox.com/en/solutions/personal-apps/secure-folder) ([Enhancer](#knoxpatch-enhancer) might be required)
- ✅ [Secure Wi-Fi](https://www.samsung.com/uk/support/mobile-devices/what-is-the-secure-wifi-feature-and-how-do-i-enable-or-use-it/)
- ➖ [Smart View](https://www.samsung.com/uk/tvs/tv-buying-guide/what-is-samsung-smart-view/) ([Enhancer](#knoxpatch-enhancer) required)
- ✅ [Private Share](https://www.samsung.com/uk/support/mobile-devices/how-to-keep-your-personal-data-safe-using-private-share/)
- ❌ [Samsung Pass](https://www.samsung.com/uk/apps/samsung-pass/)
- ❌ [Samsung Wallet (Pay)](https://www.samsung.com/uk/apps/samsung-wallet/)

## KnoxPatch Enhancer

KnoxPatch Enhancer is a flashable zip that will take care of the (currently) non-fixable apps/features via the Xposed API's. There are two different install modes:

- Via the [Magisk](https://github.com/topjohnwu/Magisk)/[KernelSU](https://github.com/tiann/KernelSU) app (fix Galaxy Wearable apps/Smart View):

  Download the module zip from the [latest release](https://github.com/BlackMesa123/KnoxPatch/releases/latest) and install it from the "Modules" tab inside the Magisk/KernelSU app. The app will then show an "Enhanced" badge if the module is installed and active:

<p align="center">
  <img src="https://raw.githubusercontent.com/BlackMesa123/KnoxPatch/main/readme-res/kp-enhancer.jpg" width="35%" />
</p>

- Via a custom recovery (fix Secure Folder on legacy devices):

  Legacy devices running One UI 2.x or 3.x with [FBE](https://source.android.com/docs/security/features/encryption/file-based) require additional patches in the system partition to fix Secure Folder. Download the module zip from the [latest release](https://github.com/BlackMesa123/KnoxPatch/releases/latest) and install it via a custom recovery, this will apply the necessary patches to fix Secure Folder. The zip will also create a backup of your original system files, flashing it again will restore them.

## Credits
- Samsung
- [LSPosed Team](https://github.com/LSPosed)
- [YukiHookAPI](https://github.com/fankes/YukiHookAPI)
- [Rikka](https://github.com/RikkaApps)

## Copyright
```
/*
 * Copyright (C) 2022 BlackMesa123
 *
 * This program is free software: you can redistribute it and/or modify
 * it under the terms of the GNU General Public License as published by
 * the Free Software Foundation, either version 3 of the License, or
 * (at your option) any later version.
 *
 * This program is distributed in the hope that it will be useful,
 * but WITHOUT ANY WARRANTY; without even the implied warranty of
 * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 * GNU General Public License for more details.
 *
 * You should have received a copy of the GNU General Public License
 * along with this program.  If not, see <http://www.gnu.org/licenses/>.
 */
```
