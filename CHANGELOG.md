# Changelog

## [1.2.7] - 2021-02-22

- Added the ability to limit the maximum retries.

## [2.0.0-nullsafety] - 2021-02-17

- Supports null safety

## [1.2.6] - 2021-01-03

- Fixed to pop after biometric authentication and then call the unlocked function.

## [1.2.5] - 2021-01-02

- Fixed to center the screen content.

## [1.2.4] - 2020-07-29

- Fixed an exception when deleting input.

## [1.2.3] - 2020-07-29

- Fix a missing exception in onUnlocked.

## [1.2.2] - 2020-07-28

- Fix exception for onUnlocked.

## [1.2.1] - 2020-07-08

- Added custom biometric button.

## [1.2.0] - 2020-07-08

- Added unlocked callback function.
- Deprecate biometricFunction. Instead, we have a biometricAuthenticate.
- If you return true with biometricAuthenticate, you can set onUnlocked to Callback. Also, Navigation.pop is now automatic.

## [1.1.2] - 2020-05-10

- Added the ability to customize buttons and backgrounds.

## [1.1.1] - 2020-05-10

- Fix to call showBiometricFunction when the animation is complete

## [1.1.0+1] - 2020-03-03

- Added video for confirm screen

## [1.1.0] - 2020-02-28

- New feature in verification passcode

## [1.0.0+2] - 2020-02-18

- Change example readme

## [1.0.0+1] - 2020-02-17

- Fix readme

## [1.0.0] - 2020-02-16

- First release

### Features

- Any number of digits can be specified
- You can change `Cancel` and `Delete` text
- The UI expands and contracts according to the size of the device
- You can disable cancellation
- You can use biometrics
- Biometrics can be displayed on first launch
- Verification passcode
- Unlocked callback
