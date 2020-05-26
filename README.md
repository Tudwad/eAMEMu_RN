# eAMEMu_RN-English

* [@juchan1220](https://github.com/juchan1220/eAMEMu_RN) (forked from juchan1220)

Android-only e-AMUSEMENT PASS emulation app using HCE-F (with React Native)

Download and install [Pre-built APK](https://github.com/Tudwad/eAMEMu_RN-English/releases).

## Precautions before use

** It is highly unlikely to work with overseas manufacturer's devices or custom ROM devices.
** When using a plastic case that completely covers the NFC antenna section (usually on the back of the unit), the recognition rate may deteriorate significantly. **

1. In order to run the app, you need a device with NFC with Android 8.0 or higher. In addition, each device requires a function with different compatibility (HCE-F). Even with NFC, you may not be able to emulate the card.
2. When using this app, we recommend that you activate NFC and close apps that use other card emulation (such as mobile T-money). Also, please set the default NFC setting on some devices to the Android operating system or automatic selection.
3. Please note that the SID does not match the earmuff card number. The card number is displayed in the preview or 'touch to activate / deactivate' in the home.
4. SID cannot be entered directly and can only be generated at random. It's really lucky that a randomly generated card may already be in use, so you can change the SID back to random at that time.
5. To prevent abuse due to indiscreet card creation, there are 5 card creation restrictions per day. Please be careful to use.

## Devices that have been confirmed to operate normally
* Galaxy Note 8 (SM-N950N), Android 9
* Galaxy Note 9 (SM-N960N), Unknown
* LG V30 (LGM-V300L), Android 9
* Galaxy S10 5G (SM-G977N), Android 10

## Device not working during testing
** This list is for reference only and may work properly even if it is listed below depending on the execution environment **

* XPERIA XZ2 Compact, Android 9
* Mi Note 3, Android 9

### Special Thanks for 
* [@dogelition_man](https://github.com/ledoge) (provide source that convert sid to card number)

Build May/Will Fail, Please just download the app-release.apk until further notice.
