# Simpl Android OneClick SDK
## Release Notes
### v2.0.7
- [Approval v1.0.28](https://github.com/GetSimpl/simpl-android-maven-repo/blob/master/com/simpl/android/approvalSDK/changelog.md#v1028)
### v2.0.6
- [Fingerprint v1.0.23](https://github.com/GetSimpl/simpl-android-maven-repo/blob/master/com/simpl/android/fingerprintSDK/changelog.md#v1023)
### v2.0.5
- [Fingerprint v1.0.22](https://github.com/GetSimpl/simpl-android-maven-repo/blob/master/com/simpl/android/fingerprintSDK/changelog.md#v1022)
### v2.0.4
- Authorization callback in UI Thread
- [Approval v1.0.25](https://github.com/GetSimpl/simpl-android-maven-repo/blob/master/com/simpl/android/approvalSDK/changelog.md#v1025)
### v2.0.3
- [Approval v1.0.24](https://github.com/GetSimpl/simpl-android-maven-repo/blob/master/com/simpl/android/approvalSDK/changelog.md#v1024)
### v2.0.2
- [Approval v1.0.23](https://github.com/GetSimpl/simpl-android-maven-repo/blob/master/com/simpl/android/approvalSDK/changelog.md#v1023)
- Added exception handler
### v2.0.1 & v1.1.37
- [Approval v1.0.22](https://github.com/GetSimpl/simpl-android-maven-repo/blob/master/com/simpl/android/approvalSDK/changelog.md#v1022)
- Fixes SMS Retriever proguard issue
### v2.0.0 & v1.1.36
- [Approval v1.0.21](https://github.com/GetSimpl/simpl-android-maven-repo/blob/master/com/simpl/android/approvalSDK/changelog.md#v1021)
- SMS Retriever API integration.
### v1.1.35
- [Approval v1.0.20](https://github.com/GetSimpl/simpl-android-maven-repo/blob/master/com/simpl/android/approvalSDK/changelog.md#v1020)
### v1.1.34
- [Approval v1.0.19](https://github.com/GetSimpl/simpl-android-maven-repo/blob/master/com/simpl/android/approvalSDK/changelog.md#v1019)
### v1.1.33
- [Approval v1.0.18](https://github.com/GetSimpl/simpl-android-maven-repo/blob/master/com/simpl/android/approvalSDK/changelog.md#v1018)
### v1.1.31
- [Approval v1.0.16](https://github.com/GetSimpl/simpl-android-maven-repo/blob/master/com/simpl/android/approvalSDK/changelog.md#v1016)
### v1.1.29
- Added dynamic permission
### v1.1.28
- [Approval v1.0.13](https://github.com/GetSimpl/simpl-android-maven-repo/blob/master/com/simpl/android/approvalSDK/changelog.md#v1013)
### v1.1.27
- Permission Request mismatch issue
### v1.1.26
- Fingerprint instance creation issue.
### v1.1.25
- Flag added to restrict data collection from device
### v1.1.24
- Fingerprint init bug fix
### v1.1.23
- Fixed proguard issues
### v1.1.22
- SDK can also be initialized programmatically.
### v1.1.21
- Removed playservices and added Location Manager for Location updates
- Refactoring of codes
### v1.1.20
- Removed ACCESS_WIFI_STATE permission
### v1.1.19
- Removed permissions from fingerprinting SDK
### v1.1.18
- Modular SDK integration
### v1.1.17
- Removed permissions from SDK
### v1.1.16
- Resolved Warning during Build of SDK
- Added survey button support during backpress in transaction flow.

### v1.1.15
- Added fingerPrint headers and Bug fixes

### v1.1.11.1
- Minor crash fix due to No GPS device
- Auto read OTP fix

### v1.1.11
- Added Redirection flow (in case of Payment due/Exceed Limit)
- Added new Method with no amount param in Subscriptions flow

### v1.1.10
- Added Subscriptions flow

### v1.1.9
- Fixed Parcel related issue for devices below 1.1.9

### v1.1.8
- Removed SimplButton that was deprecated in the last release.
- Added new gateway in SMS listener

### v1.1.7
- Deprecated SimplUserApprovalListener and added new SimplUserApprovalListenerV2 with button_text as param to be used in the UI.

### v1.1.6
- Fixed OTP auto-fill issue

### v1.1.5
- Added new microservice endpoint for approval api call

### v1.1.4
- Bug fixes related with SimplSession
- More precise tracking of errors during SDK to Merchant App Communication

### v1.1.3
- Bug fixes related with web view rendering and webview client

### v1.1.2
- Replaced READ_SMS permission with RECEIVE_SMS

### v1.1.1
- Fixed issues related with loader dialog
- Some minor bug fixes

### v1.1.0
- Now the Airbrake notifier just notifies the exceptions caused because of Simpl SDK
- Sister release of 1.0.15, with new way of communicating with Simpl SDK. Most of the previous
APIs are deprecated now (they work, but not recommended to be used). Older APIs will stop working
 from March 2016.
- Added flag system to Simpl SDK
- Now we track Location and mobile device info along with API calls to protect transactions
 against fraud
- Added fix for known SSL handshake bug for devices lower than 4.4. (http://stackoverflow.com/questions/29916962/javax-net-ssl-sslhandshakeexception-javax-net-ssl-sslprotocolexception-ssl-han)
- Fixed some minor bugs
- Fixed OTP reader logic for parsing all endpoints of the SIMPLX sms gateway

### v1.0.17
- DismissLoader helper method to remove ongoing loader issues
- Some bug fixes in webview client.
- Fixed http://stackoverflow.com/questions/29916962/javax-net-ssl-sslhandshakeexception-javax-net-ssl-sslprotocolexception-ssl-han

### v1.0.16
- Fixed wrong thread issue for showing SimplButton

### v1.0.15
- I never made it to the production :(

### v1.0.14
- Fixed loader related issue

### v1.0.13
- Fixed bug related with listeners for some edge cases

### v1.0.12
- Update proguard config for the SDK
- Removed some overlapping dependency

### v1.0.11
- Fixed loader issues

### v1.0.10
- Minor bug fixes
- Loader related UI fixes
- Now handles mailto url actions

### v1.0.9
- ProgressDialog is shown for the webview url loading

### v1.0.8
- onCancelled callback is removed from the listener
- Automatic closing of the confirmation page is added. The default time is 3 seconds.

### v1.0.7
- onCancelled callback is deprecated now. That code block will never be called during the SDK flow.

### v1.0.6
- Added authorizeTransaction method for using custom button/view to trigger transaction authorization.

### v1.0.5
- Bug fixes
   - Fixed the button height issue related with Cynogenmod.
   - Fixed the dpToPx conversion for simpl__simpleButtonHeight attribute
   - Fixed the scaling issue related with Simpl logo on SimplButton
   - Fixed the scrolling issue on the account activation page
- Added ripple effect on SimplButton (for LOLLIPIP+ devices)i
- simpl_separatorColor is now deprecated. simpl_buttonShadowColor will be used as separator color from 1.0.5.

### v1.0.4
- Removed Crittercism and shifted error logging on Airbrake
- Reduced size of SDK : Now its 188 KB including all dependencies.

### v1.0.3
- Reduced Target Compile SDK version to 22.0.1
- Reduced Build Tool version to 22.0.1
- Super slim SDK, no thrid party library dependency.
- Elaborated error messages sent through onError.
- Added onCancelled callback to detect if user has cancelled the transaction in-between.

### v1.0.2
- Added customization method and styled attribute for SimplButton title text.
- Added ```SimplSession```, a simple storage system across the activites.

### v1.0.1
- Added customizations support to Buy with Simpl button
- Customizations can be done using Java methods of SimplButton or using stylable provided with verison 1.0.1.

### v1.0.0
- First production release
- Web view based flow
- Automatic OTP detection
