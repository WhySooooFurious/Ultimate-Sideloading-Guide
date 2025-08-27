# Common Issues and fixes :)

This document lists common problems when sideloading apps on iOS and how to fix them.

## 1. “Unable to verify” error

- **Problem**: PPQ is blocked by the DNS at the initial set up 
- **Fix**: Go to **Settings → General → VPN & Device Management** → **DNS** Change that to „INSTALL ONLY“ and then try again it may take a few seconds to apply 

## 2. App crashes immediately after opening

- Often caused by expired certificates/broken .ipa 
- **Fix**: Either switch the certificate to a other one or try to get a other .ipa you try to install 

## 3. Portal singer says a error 

- It can happen because of a problem with the API or your WiFi connection isn’t stable 
- **Fix**: You can use 3 options
  1. [https://wsfteam.xyz/#signer](https://wsfteam.xyz/#signer)
  2. [https://sign.ipasign.cc/](https://sign.ipasign.cc/)
  3. [https://sign.kravasign.com](https://sign.kravasign.com)

## 4. Installation fails

- Causes: unsupported IOS version, corrupted .ipa
- **Fix**: Ensure the .ipa is compatible with your iOS version and make sure the .ipa is working 

## 5. The config is shown as „not signed“ 

- that’s normal since they aren’t signed by Apple and they probably won’t be so don’t worry ;)

## 6. Unable to Install "Resident **Evil 4" Please try again later.**

- Cause: Even if you did everything correctly, iOS sometimes caches a failed validation from a previous attempt.
- Fix: Reboot your device and try installing again.
