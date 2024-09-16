# Ultimate-Sideloading-Guide 

# IN PROGRESS, MIGHT NOT WORK FOR YOU, INSTALL THE DNS AT YOUR OWN RISK, APPS MAY GET REVOKED AS IT IS INCOMPLETE!
# THE GUIDE IS IN PROGRESS DO NOT USE!!! 
## I will remove all of these warnings AFTER the guide is done!

## Introduction
Hello, Welcome to my guide on how to sideload on Apple Devices using a method I came across to a while back. This sideloading method has worked for long periods of time, without any app limits and without a pc. I eventually found some small let-downs such as the DNS at the time was and is still made by some random vietnamese guy with no open-sourced data which naturally has some privacy concerns. ESign also has been widely accused of stealing data. After a few months of using both of these services I decided to reverse-engineer the DNS and how the enterprise signed ESign was downloaded over the web with the click of a button. With enabling better preventions against revokes unlike other people who keep on using other people's DNS and put no effort in themselves with bad instructions to say the least. 

Without further ado, welcome to my Ultimate Sideloading Guide, if you have any issues, requests or ideas please make an issue.

## Compatibility
This should work for all iOS, iPadOS and even macOS devices, on the latest versions of all iOS, iPadOS and macOS.

Versions that might not be supported are below iOS 12, iPadOS 13 and macOS 11.

## How does this method work?
WhySooooFurious DNS Blocker: This is the base of everything. This blocks Apple from revoking your enterprise signed apps. Preventing them from being revoked permanently. 

ESign: An app manager which uses leaked enterprise business certificates to get apps running in your device in the first place


## Before we start
- Make sure you have not been using services such as Scarlet before as the certificates used by me will be revoked!. 
- This method will work as long as you do all of the steps required and never disable the DNS which is the main thing. 
- If you are blacklisted from Apple for already using services such as Scarlet you will need to follow this [guide](#revoked-or-blacklisted)
- Make sure your device is compatible as seen [here](#compatibility)

## Part [1/3] Installing the WhySooooFurious DNS Blocker
Note: I will eventually put visual aids in the guide itself
1. Go down to [Downloads](#downloads) and click on the WhySooooFurious DNS Blocker, allow the download and close the prompt
2. Now, open settings and go to General>VPN & Device Management
3. Click on the downloaded profile and install it, you may need to input your password
4. The DNS should now automatically be enabled, Do not change the DNS to automatic otherwise your apps will get revoked!
5. Now go back and then go to General>About>Certificate Trust Settings
6. Enable Full trust for the NextDNS Root Certificate

## Part [2/3] Installing ESign
Note: I will eventually put visual aids in the guide itself
1. Go down to [Downloads](#downloads) and click on ESign Direct Install
2. Click on install once the popup comes up
3. Open settings and go to General>VPN & Device Management
4. Select the HDFC app and click on Trust
5. Click on allow, after this your device might need to be restarted
6. If your device was restarted, swipe up and click on install profile
7. ESign should now be on your home screen, fully functional

## Part [3/3] Setting up ESign






















## Q/A

**Q -** Won't a VPN bypass the DNS and revoke my apps?

**A -** It shouldn't be, based on the settings I used, I still do not recommend using a VPN at all. If you need to use a VPN, Use this [guide](#using-a-vpn)


---

**Q -** Will a restart bypass the DNS and revoke my apps?

**A -** Simple answer, No.

---

**Q -** OMG, Are you going to track my furry content?

**A -** No, I have no need to look at your expenditures.

---

**Q -** Um, I'm a big-time dev and I need to look at your code thingies to ensure they don't have viruses

**A -** Sure! Go over [here](https://shorturl.at/zHEbJ) to look at what is used in the process!

---

**Q -** Can I see the NextDNS settings used?

**A -** Yes, make an issue and mention your email and I will send you a viewing invitation.

---
















































## Downloads
[WhySooooFurious DNS Blocker](https://shorturl.at/fwIJk)

[ESign Direct Install](https://shorturl.at/Jx5gX)

# Miscellaneous Guides

## Using a VPN 
So you want to use a VPN with the DNS blocker, follow the steps below and you should be able to use your VPN normally and on-demand, I still do not recommend using a VPN with the DNS, You should know how to configure your VPN's DNS server yourself as there are different steps for each VPN supplier

### Method 1
1. 45.90.28.51 and 45.90.30.51 are the DNS servers you need to replace in your VPN's settings

## Revoked? or Blacklisted?
So you've gotten yourself blacklisted, either from my DNS (which seems very unlikely) or from another creator's DNS. Follow the methods listed below and you should be unrevoked. 

Use method 2 if method 1 does not work

You must not use your backups with method 2 otherwise you will get revoked again

### Method 1
1. Back up your device, here is a [guide](https://support.apple.com/en-us/118426)
2. After backing up, reset your device, here is a [guide](https://support.apple.com/en-au/guide/iphone/iphea1c2fe48/ios)
3. Now if you have an iCloud backup you should be prompted to restore from your backup after logging in to your Apple ID, if you have a local backup all you need to do is plug your phone in, go on either Finder for macOS or iTunes for Windows and click on restore backup from your device's menu
4. Then follow the guide for Part 1 of the WhySooooFurious DNS Blocker to prevent revokes in the future

### Method 2
1. Follow this [guide](https://support.apple.com/en-au/guide/iphone/iph7a2a9399b/ios)
2. Then follow the guide for Part 1 of the WhySooooFurious DNS Blocker to prevent revokes in the future

## ESign Sources
My sources for ESign                    
###
    source[5GHxhb1U7Lc5jIMpumASbN2teg9dyK5EAazzwnfm1/gPKQPTWzcz/GqmMyJ96qOpN9I+sobaxc2bOxLJOnEOvCBO0S3fPLfBifsFqblxWBSpvpIt92QQghflQC3w+Exfmk/TRgDUpbmR0WYET6IlVgzUUt7zvQnk7OiXHlKE211IckI8xJGGbC6i4pHK7a2i7uAzEJjZ612XcSAUVA/z9d09OYgTx3UQwP6vQ6pG/tTT6Miy/oiQOfn4EY1keR6ER2m4J09StZmkEnFVBn2x+CED9WuUY6lqPIE/qSQ+ituWE6E67AbhSk4crGGNzlcO9PoeyHjGA3w+SQVoiVbgetHxdx0c4fdqt+GG0vZvZK7TLp7iWFgDcewQhC9MEOuzVfQy267Uy7Ag6VAw37qcUP/WJOkbUuFRGUgICFesTlR1BDRsQyOmT3jek2XBLBC8nVR7EQlgm6Ggkf3bOhm3OBi/dHxwbtB4zPa8l3TyAwp8rhDwsE493pH84s84Bfws5KQNh2/XQRVRL4CwnkUe1eljMIZgewKrS0GR37coqecAkiPJNnurDLN0nqf5ddRd0d3+9wl40Q8LPv2vuBWk0mqwlgDaLwmJK1ZmT/ikcagjd79u3RoQo3uSZHJbGPA/WoDgxLHGPcPgC0DgzBu3/8D1dmp3nzzUtNppbr7IJkdmizglxmitKG6jbbMylxEDcBcu/b33wu2E8AsL31mm33Ce05UtkFWT5xYaGe07XqM9dPo7kO/3+eFnEhCOThXkUTPHC7WlXJDf1kh+jG9ikzIpl8ku2nu1/cbb+o+mYbSyHTSQN54VHk5agiLC91gnHiqL5Mp9p7JCm9KWpkZKZ4oaRNwgh+y04wynnWH0duxNz+h/vpmBL/m5dDZP0KQxlVTKqS0IKGlwzaeg2vFxBZV6SqM7BT7Ik2sfMXcNTQEnDvUvafsxMmlElYFf9D0YCe1hJyIoxpbMVQPGF4oFJ+DDetcuOpnfHOO2a/49v63WUYyVwnSK6LclXpojAA3xUgU5Dp/8EWT4CAz5FZLjN2LgzyUKOt6IZdMFvYx9A8rKA/EmC6oHvMZguLFZqr3RY5eDfpNXyd/MMuBu7w/EwG/B1oc1kSL+jw0UXNyJrFR2st98Y0PSvqf2Lb0OlV3GnWeRTLMTN5N2BGoFPn7O+6p6wcZM4Y1nkEtl0Tb/8t4fT28h7oWHfdPzvP7mirQS5Piq9D5rfVOz4ZKlz0e32LjQ0lVflKKy1+IZaz9ETxov1qR55Pxg3SWLqdlHkfmqnt8Kbr0ZruSWmBfmcT5mb6MXYQWCutYMtOLkORms/uc/D3UeE+NOiIedsDB1jGQR1gqs+ZKuWy6a0v2Mq4fig0Z7JtbsxYJWhywUDo8bcs2BPF0lqt3xIpcSJOQbxf1O5TpJKVC1xbASJ5llKKaEpNdMLD5F1obewemuWQxVZl7V0qAUfvwYiC6S0ructE9h4IPsEhpdHa+JbUWQRIMMLwnZkr6p6s5mU+hNKHhaLIXcQ4XQDzDcfgpi1e61Wa/l1m05ZQQxz6bh+20sWsVOlb+hYehOi5GMep1dgCO54C5ViA/4j75WSBHbB4YpkovZpgwBxJlge27DdhicPti1Io+ZMpYfygGl0iJy8o4aUEKYbvsSpZjZX+Jf9xM3L3Ji+8FUMo+1sLdCmRrQAyWZ9L2ZafEE6zCKxA9tPZ/91DvcX1slwfzEas2Kyk27aXYSvQI4bf6Dpt7y05R9bKrxn6db28bVIURKr5pm8TcBJH62wOTN6sfC2MPYf6wXi66EsrTuKA==]

## Wiki

### Sideloading
The process of installing apps on iOS or iPadOS devices from sources other than the Apple App Store. This often involves using alternative methods or tools to bypass the App Store’s restrictions.

### IPA (iOS App Store Package)
The file format used to package iOS applications for distribution and installation. Sideloading an app typically involves downloading an IPA file and using tools to install it on the device.

### Provisioning Profile
A file that ties an app to a specific developer account and device. It includes certificates and app-specific permissions. When sideloading an app, the provisioning profile ensures the app is allowed to run on the target device.

### Enterprise Certificate
A special type of certificate used by organizations to distribute apps internally to employees. Enterprise certificates are managed through the Apple Developer Enterprise Program and allow sideloading apps outside the App Store for internal use. Misuse of enterprise certificates for distributing apps to the public can lead to revocation by Apple.

### Developer Certificate
A certificate issued by Apple to developers, used to sign apps and verify their authenticity. Developer certificates are necessary for sideloading apps through methods like Cydia Impactor or AltStore.

### App Signing
The process of applying a digital signature to an IPA file to ensure it is trusted and verified by iOS. App signing involves using a valid developer or enterprise certificate and provisioning profile.

### UDID (Unique Device Identifier)
A unique identifier assigned to each iOS device. UDIDs are used in provisioning profiles to specify which devices are allowed to run a particular app. When sideloading apps, a UDID may be required to register the device for app installation.

### Ad-Hoc Distribution
A method of distributing iOS apps to a limited number of devices for testing or internal use. Ad-Hoc distribution involves creating a provisioning profile that includes the UDIDs of the devices allowed to install the app.

### Enterprise Distribution
A method used by organizations to distribute apps internally via an enterprise certificate. This method is intended for distributing apps within an organization, not to the general public.

### App Re-signing
The process of updating an app’s signature, often done to extend the validity of a sideloaded app. Since sideloaded apps are subject to certificate expirations, app re-signing helps maintain functionality.
