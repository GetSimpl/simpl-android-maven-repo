# Simpl Android OneClick SDK
## Release Notes
### v1.1.27
1. Permission Request mismatch issue
### v1.1.26
1. Fingerprint instance creation issue.
### v1.1.25
1. Flag added to restrict data collection from device
### v1.1.24
1. Fingerprint init bug fix
### v1.1.23 
1. Fixed proguard issues
### v1.1.22 
1. SDK can also be initialized programmatically.
### v1.1.21 
1. Removed playservices and added Location Manager for Location updates
2. Refactoring of codes
### v1.1.20 
1. Removed ACCESS_WIFI_STATE permission
### v1.1.19 
1. Removed permissions from fingerprinting SDK 
### v1.1.18 
1. Modular SDK integration
### v1.1.17 
1. Removed permissions from SDK
### v1.1.16 
1. Resolved Warning during Build of SDK
2. Added survey button support during backpress in transaction flow.

### v1.1.15 
1. Added fingerPrint headers and Bug fixes

### v1.1.11.1 
1. Minor crash fix due to No GPS device
2. Auto read OTP fix

### v1.1.11 
1. Added Redirection flow (in case of Payment due/Exceed Limit)
2. Added new Method with no amount param in Subscriptions flow

### v1.1.10 
1. Added Subscriptions flow

### v1.1.9 
1. Fixed Parcel related issue for devices below 1.1.9

### v1.1.8 
1. Removed SimplButton that was deprecated in the last release.
2. Added new gateway in SMS listener

### v1.1.7 
1. Deprecated SimplUserApprovalListener and added new SimplUserApprovalListenerV2 with button_text as param to be used in the UI.

### v1.1.6 
1. Fixed OTP auto-fill issue

### v1.1.5 
1. Added new microservice endpoint for approval api call

### v1.1.4 
1. Bug fixes related with SimplSession
2. More precise tracking of errors during SDK to Merchant App Communication

### v1.1.3 
1. Bug fixes related with web view rendering and webview client

### v1.1.2 
1. Replaced READ_SMS permission with RECEIVE_SMS

### v1.1.1 
1. Fixed issues related with loader dialog
2. Some minor bug fixes

### v1.1.0 
1. Now the Airbrake notifier just notifies the exceptions caused because of Simpl SDK
2. Sister release of 1.0.15, with new way of communicating with Simpl SDK. Most of the previous
APIs are deprecated now (they work, but not recommended to be used). Older APIs will stop working
 from March 2016.
 3. Added flag system to Simpl SDK
 4. Now we track Location and mobile device info along with API calls to protect transactions
 against fraud
 5. Added fix for known SSL handshake bug for devices lower than 4.4. (http://stackoverflow.com/questions/29916962/javax-net-ssl-sslhandshakeexception-javax-net-ssl-sslprotocolexception-ssl-han)
 6. Fixed some minor bugs
 7. Fixed OTP reader logic for parsing all endpoints of the SIMPLX sms gateway

### v1.0.17 
1. DismissLoader helper method to remove ongoing loader issues
2. Some bug fixes in webview client.
3. Fixed http://stackoverflow.com/questions/29916962/javax-net-ssl-sslhandshakeexception-javax-net-ssl-sslprotocolexception-ssl-han

### v1.0.16 
1. Fixed wrong thread issue for showing SimplButton

### v1.0.15 
1. I never made it to the production :(

### v1.0.14 
1. Fixed loader related issue

### v1.0.13 
1. Fixed bug related with listeners for some edge cases

### v1.0.12 
1. Update proguard config for the SDK
2. Removed some overlapping dependency

### v1.0.11 
1. Fixed loader issues

### v1.0.10 
1. Minor bug fixes
2. Loader related UI fixes
3. Now handles mailto url actions

### v1.0.9 
1. ProgressDialog is shown for the webview url loading

### v1.0.8 
1. onCancelled callback is removed from the listener
2. Automatic closing of the confirmation page is added. The default time is 3 seconds.

### v1.0.7 
1. onCancelled callback is deprecated now. That code block will never be called during the SDK flow.

### v1.0.6 
1. Added authorizeTransaction method for using custom button/view to trigger transaction authorization.

### v1.0.5 
1. Bug fixes
   - Fixed the button height issue related with Cynogenmod.
   - Fixed the dpToPx conversion for simpl__simpleButtonHeight attribute
   - Fixed the scaling issue related with Simpl logo on SimplButton
   - Fixed the scrolling issue on the account activation page
2. Added ripple effect on SimplButton (for LOLLIPIP+ devices)i
3. simpl_separatorColor is now deprecated. simpl_buttonShadowColor will be used as separator color from 1.0.5.

### v1.0.4 
1. Removed Crittercism and shifted error logging on Airbrake
2. Reduced size of SDK : Now its 188 KB including all dependencies.

### v1.0.3 
1. Reduced Target Compile SDK version to 22.0.1
2. Reduced Build Tool version to 22.0.1
3. Super slim SDK, no thrid party library dependency.
4. Elaborated error messages sent through onError.
5. Added onCancelled callback to detect if user has cancelled the transaction in-between.

### v1.0.2 
1. Added customization method and styled attribute for SimplButton title text.
2. Added ```SimplSession```, a simple storage system across the activites.

### v1.0.1 
1. Added customizations support to Buy with Simpl button
2. Customizations can be done using Java methods of SimplButton or using stylable provided with verison 1.0.1.

### v1.0.0 
1. First production release
2. Web view based flow
3. Automatic OTP detection
