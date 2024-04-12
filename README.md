<div align="center">
  <img src="https://github.com/hamzaharoon1314/SnapEnhanceModGen/blob/9aba3263a34893c91a08d86183baf708bbbbea9c/REDME_IMG/LOGO.png" height="250">
</div>

### [Instuctions](#instructions) Below (Including [Obtainium Instructions](#obtainium-instructions))

The Workflow runs at 23:55 UTC (6:55 PM EST or 7:55 PM EDT, Eastern Daylight Savings Time) only on Sunday and Thursday. (Subject to change, mainly when I'm testing.)

# SnapEnhance LSPatch
SnapEnhance is an Xposed mod that enhances your Snapchat experience.

This ***unofficial*** repository uses a GitHub Actions workflow for generating a Snapchat APK by using the [SnapEnhance Module](https://github.com/rhunk/SnapEnhance) and creating a public release.

Credit to [@hamzaharoon1314](https://github.com/hamzaharoon1314) and [@ABCPascal](https://github.com/ABCPascal) for much of the work.

### [@NicholasFlamy](https://github.com/NicholasFlamy)'s Work:
- Fully automated this repository
- Display Snapchat & SnapEnhance version
- New release created for every workflow run
- Release version follows SnapEnhance
- Multiple Architectures in Releases
- More...

<br>

# Instructions
The instructions are on every [release](https://github.com/NicholasFlamy/snapenhance-no-root-patch/releases/latest).
- If you don't know your device's architecture [click here](https://github.com/NicholasFlamy/snapenhance-no-root-patch/blob/master/LEARNFINDARCH.md).

<br>

# Obtainium Instructions
COMING SOON (not ™ as I will post Obtainium config for this once I get it working, I personally use Obtainium)

<h2 href="obtainium://app/%7B%22id%22%3A%22me.rhunk.snapenhance%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2FNicholasFlamy%2Fsnapenhance-no-root-patch%22%2C%22author%22%3A%22NicholasFlamy%22%2C%22name%22%3A%22SnapEnhance%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Atrue%2C%5C%22dontSortReleasesList%5C%22%3Atrue%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22v(%5C%5C%5C%5Cd%2B)%5C%5C%5C%5C.(%5C%5C%5C%5Cd%2B)%5C%5C%5C%5C.(%5C%5C%5C%5Cd%2B)%5C%5C%5C%5C.(%5C%5C%5C%5Cd%2B)%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%241.%242.%243%5C%22%2C%5C%22versionDetection%5C%22%3Atrue%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22%5Esnapenhance-.*%3F%5C%5C%5C%5C.apk%24%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Atrue%2C%5C%22appName%5C%22%3A%5C%22SnapEnhance%5C%22%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22%5C%22%7D%22%7D">test


<br>

## SnapEnhance and Snapchat Update Instructions

### SnapEnhance Update
1. Clear/Regenerate Mapping File after update?

### Snapchat Update
1. Clear/Regenerate Mapping File after update?

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
