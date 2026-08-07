# MultiLock Android

A simple Android app-lock project:
- Select any installed app.
- Add 1, 2, 3 ... as many sequential PIN locks as you want.
- Save.
- When the protected app comes to the foreground, the PIN sequence appears one by one.
- PINs are stored as SHA-256 hashes, not plaintext.

## Build
1. Open this folder in Android Studio.
2. Let Gradle sync.
3. Build the APK.
4. Install it on the phone.
5. Open MultiLock.
6. Add an app and create its PIN sequence.
7. Enable MultiLock under Android Settings > Accessibility.
8. Open the protected app.

## Important
Android OEMs can restrict Accessibility services or background activity launches. On Xiaomi/MIUI/HyperOS, you may need to allow MultiLock to run in the background and disable battery restrictions for it.

This is a starter implementation. Test on the target Android version/device before relying on it for security.
