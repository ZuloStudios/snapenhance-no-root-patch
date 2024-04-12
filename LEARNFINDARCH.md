### If you don't know what architecture your device has (arm64-v8a or armeabi-v7a)
Check your architecture:
1. Install [Device Info HW](https://play.google.com/store/apps/details?id=ru.andr7e.deviceinfohw)
2. Open the app
3. Go to the SoC tab
4. Look for ABI (it should show arm64-v8a or armeabi-v7a)
    - If it shows arm64-v9a that's an improvement to arm64-v8a so use arm64-v8a.

Alternatively:
- Install the **universal** apk which takes up a little more space because it includes both architectures.
