<div align="center">
  <img src="https://github.com/hamzaharoon1314/SnapEnhanceModGen/blob/9aba3263a34893c91a08d86183baf708bbbbea9c/REDME_IMG/LOGO.png" height="250" />

### [Instuctions](https://github.com/NicholasFlamy/snapenhance-no-root-patch#instructions) Below (Including [Obtainium Instructions](https://github.com/NicholasFlamy/snapenhance-no-root-patch#instructions-for-obtainium-users))

# SnapEnhance LSPatch Generator
SnapEnhance is an Xposed mod that enhances your Snapchat experience.<br/><br/> This is Un-Offical repo to build the LSPatch Version.
</div>

### SnapEnhanceModGen

This repository contains a GitHub Actions workflow for generating a Snapchat APK by using the [SnapEnhance Module](https://github.com/rhunk/SnapEnhance) and creating a public release.

<br>

# Instructions
The instructions are on every release, download the `patched-snapchat.apk` file and the correct version of SnapEnhance (a link will be in the release notes.)
   - (If you don't know what architecture -- armv8 or armv7 -- to download, check out [this app](https://play.google.com/store/apps/details?id=ru.andr7e.deviceinfohw), go to the SoC tab and look for ABI as it will show you which architecture your phone uses. If you have armv9 that's an improvement to armv8 so use armv8.)

<br>

# Instructions for Obtainium Users
COMING SOON (not TM as I will post Obtainium comfig for this once I get it working, I personally use Obtainium)

<br>

## SnapEnhance and Snapchat Update Instructions

### SnapEnhance Update
1. Clear/Regenerate Mapping File after update.

### Snapchat Update
1. Clear/Regenerate Mapping File after update.

<br>

## How the Github Action works:

This GitHub Actions workflow automates the creation of a Snapchat Patch for Non-Root users. Here's how it works:

1. **Snapchat Download**: The action downloads the latest stable version of Snapchat from APKMirror.

2. **SnapEnhance Download**: It also fetches the latest version of SnapEnhance from the original repository.

3. **Patch Build**: The action then builds the patch version of Snapchat.

4. **Upload to Release**: Finally, it uploads the patch to a new GitHub Release with the first 3 parts of the version matching the SnapEnhance version.

<br>

## How to report issues

Do not report issues of these prebuilts in the official [SnapEnhance Telegram](https://t.me/snapenhance_chat). If you want me to help (@NicholasFlamy) then you need to open an issue on this repo. 

You could also make a post about it on [r/SnapEnhanceApp](https://reddit.com/r/SnapEnhanceApp) using the "Prebuilt Issue" post flair or make a post about it on the [SnapEnhance Lemmy Community](https://lemmy.world/c/snapenhance) mentioning that it's a prebuilt.

<br>

## Contributing

You can feel free to contribute to this project by opening issues and pull requests.
