<h2>Version Information:</h2>
Snapchat Version: ${{ steps.REGEX_snapchat_version.outputs.replaced }}
<br>
SnapEnhance Version: ${{ env.snapenhance_release_tag_name }}
<br>
<h3>Instructions:</h3>
If you want to use SnapEnhance Snapchat on Android without root, then you need to download `${{ env.patched_apk_filename }}` and `${{ env.snapenhance_apk_filename }}` and install them.
