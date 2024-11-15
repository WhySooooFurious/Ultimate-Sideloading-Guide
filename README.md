# Join this Discord [server](https://discord.gg/kwvwkCBhxT) for updates regarding everything!

# Use this [website](https://whysoooofurious.github.io/Ultimate-Sideloading-Guide/) instead of Github!

## Introduction
Welcome to my guide on how to sideload on Apple Devices!
Some of the advantages with using this method:

- Free!

- No PC!

- Easy to use!

- No App Limits!

- On Device Signing!

- No Privacy Concerns!

- Takes 5 Minutes to Setup!

- Compatible with Scarlet/Feather/ESign/GBox

If you have any issues, requests or ideas please make an issue on GitHub or Discord.

## How does this method work?
By using leaked business enterprise certificates, We can sign apps using their credentials which means Apple lets us install the apps without any hassle, however after a while Apple revokes the certificate which can be easily bypassed by using this method.

## Before we start

- This might not work for you if you've been using other enterprise sideloaders as the certificates might be revoked on your device!

- If you are revoked you will need to follow the the Revoked guide!

- This will work as long as you read and do all of the steps properly!

- WhySooooFurious = WSF

## Compatibility
This should work for all iOS and iPadOS devices on the latest versions, won't work for iOS 15 and below. The guide is compatible with other sideloading services as long as they rely on enterprise certificates to install.

## Privacy
If you have privacy concerns about the madNS Config Profile, make an issue on github with your email and i'll send you a viewing invite so you can see the settings for yourself.

Make sure to mention exactly what the madNS's profile name is:

e.g:

madNS Config Profile + Update Blocker
or
madNS Config Profile + Update Blocker + Ad-Blocker

The WSF Config Profile isn't a DNS but just redirects Apple Servers to https://localhost.direct which is your local network, so no privacy concerns.

## Starting the guide!

### Which Config Profile do I choose?
The WSF Config Profile redirects Apple servers to https://localhost.direct (which is your own local network) which prevents Apple from contacting your device about the revoked certificate.
Additionally, the WSF Config profile supports the following:

- iOS Update Blocking

The madNS Config Profile supports VPNs, Feather and ChatGPT which can be a deciding factor.
Additionally, the madNS Config Profile supports the following: 

- Ad-Blocking

- iOS Update Blocking

Make sure you don't have any VPNs turned on during the installation even when using the madNS Config Profile. Note you will need the set up your VPN using the guide in Portal

### Part [1/2] Installing the Config Profile
1. Go down to [Downloads](#downloads) and click on the link, then Config Profiles and then select the Config Profile you would like to install
2. Click on Download, and the profile should be imported into settings automatically
3. Now, open settings and go to General > VPN & Device Management and install the downloaded profile
4. It should now automatically be enabled
5. Continue onto [Part 2](#part-22-installing-portal) to install Portal

### Part [2/2] Installing the Portal App
1. Go down to [Downloads](#downloads) and click on the link, then Portal and then select any of the links, keep in mind if none of them install you need to follow this [guide](#revoked)
3. Click on install once the popup comes up
4. Open settings and go to General > VPN & Device Management > (should show the Portal app under the certificate you picked back in Step 1)
5. Click on Trust at the top then click on allow, after this your device might need to be restarted
6. If your device was restarted, swipe up and click on install profile
7. WSF Portal should now be on your home screen, fully functional
8. Now read the guides in Portal to install your chosen sideloade!

## Troublshooting

- Unverified?

- Crashing Apps? 

- App is not available? 

- Integrity could not be verified? 

You need to follow this [guide](#revoked) or alternatively you can try other download links!

---

## Downloads

Download Link is in the #links channel in the Discord [Server](https://discord.gg/kwvwkCBhxT)

## FAQ
---

Q - Can I use a VPN?

A - You can if you're utilising the madNS Config Profile, make sure to set it up first! VPN Guide is in the Portal app!

---

Q - Will a restart bypass this and revoke my apps?

A - Some users have found that on older devices, your apps might revoke, disable Wi-Fi and enable Airplane Mode when wanting to restart or shutdown.

---

Q - Will services such as AltStore, Sideloadly and Sidestore affect this guide at all?

A - No, Those listed services use developer signing instead of Enterprise signing so they are fine to use alongside! You will however need to setup the Sideloadly's WireGuard, VPN Guide is in the Portal app!

---

### Revoked?
So you've gotten yourself revoked, Follow the methods listed below and you should be unrevoked.

Method 1 will work.

Method 2 will completely reset your device and will definitely work

You must not use your backups with Method 2


#### Method 1
1. Remove the Config Profile and uninstall every app you've installed using certificates
2. Back up your device with iTunes
3. After backing up, reset your device using iTunes restore in Recovery Mode or DFU mode is heavily recommended
5. Now if you have an iCloud backup you should be prompted to restore from your backup after logging in to your Apple ID, if you have a local backup all you need to do is plug your phone in, go on either Finder for macOS or iTunes for Windows and click on restore backup from your device's menu
6. Then follow Part 1 of the guide to prevent revokes

#### Method 2
1. Remove the Config Profile and uninstall every app you've installed using certificates
2. Reset your device using iTunes using Recovery Mode or DFU mode
3. Then follow Part 1 of the guide to prevent revokes
