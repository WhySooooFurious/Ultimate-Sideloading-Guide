# Join this Discord [server](https://discord.gg/kwvwkCBhxT) for updates regarding everything!

# Use this [website](https://whysoooofurious.github.io/Ultimate-Sideloading-Guide/) instead of Github!

(Won't redirect you anywhere if you're already on it)

# Introduction

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

We have made our own app called "Portal" and it contains all links to ESign, Feather, GBox and Scarlet inside the app itself!

## Unsupported Methods

We don't support other guides that use services such as NextDNS as those have limits, and apps will revoke if you pass that limit. 

The madNS Config Profile itself uses NextDNS and is transparent as we could make it be. It is run for by donators and will keep running for as long as possible.

## Before we start

- This might not work for you if you've been using other enterprise sideloaders as the certificates might be revoked on your device!

- If you know that you are revoked you will need to follow the the Revoked guide [here]

- This will work as long as you read and do all of the steps properly!

## Compatibility

This should work for all iOS and iPadOS devices on latest iOS versions, won't work for iOS 15 and below. The guide is compatible with other sideloading services as long as they rely on enterprise certificates to install.

## Privacy

You can view the privacy report [here](https://nch.pl/s/rKBAY59pNcX5bpJ/download?path=%2F&files=maDNS%20Config%20Profile%20Privacy%20Report.pdf&downloadStartSecret=5en4k2r6yuv)

If you have still have privacy concerns about the madNS Config Profile, make an issue on github with your email and i'll send you a viewing invite so you can see the settings for yourself.



Make sure to mention exactly what the madNS's profile name is:

e.g:

madNS Config Profile + Update Blocker
or
madNS Config Profile + Update Blocker + Ad-Blocker

The WSF Config Profile isn't a DNS since just redirects Apple Servers to https://localhost.direct which is your local network, so no privacy concerns, you can verify this by opening the profile in any text editor.

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

# Starting the main guide, Read everything carefully!

## Which Config Profile do I choose?

### WSF Config Profile

Doesn't support VPN's, Feather or ChatGPT and is very privacy-oriented

### madNS Config Profile

Supports VPNs, Feather and ChatGPT.

### What does Update Blocker or Ad-Blocker mean?

Update Blocker: Blocks Apple OTA Updates

Ad-Blocker: Blocks most online Ads and Trackers

Make sure you don't have any VPNs turned on during the installation even when using the madNS Config Profile as you need to setup the VPN.

## Installation Guide

### Part [1/2] Installing the Config Profile

1. Go down to [Downloads](#downloads) and click on the link, then Config Profiles and then select the Config Profile you would like to install
2. Click on Download, and the profile should be imported into settings automatically
3. Now, open settings and go to General > VPN & Device Management and install the downloaded profile
4. It should now automatically be enabled
5. Continue onto [Part 2](#part-22-installing-portal) to install Portal

### Part [2/2] Installing Portal

1. Go down to [Downloads](#downloads) and click on the link, then Portal and then select any of the links, keep in mind if none of them install you need to follow this [guide](#revoked)
3. Click on install once the popup comes up
4. Open settings and go to General > VPN & Device Management > (should show the Portal app under the certificate you picked back in Step 1)
5. Click on Trust at the top then click on allow, after this your device might need to be restarted
6. If your device was restarted, swipe up and click on install profile
7. Portal should now be on your home screen, fully functional
8. Now read the guides in Portal to install your chosen sideloade!

## Downloads

Download Link is in the #FAQ channel in the Discord [Server](https://discord.gg/kwvwkCBhxT)

## Troublshooting

- Unverified?

- Crashing Apps? 

- App is not available? 

- Integrity could not be verified? 

You need to follow the Revoked Guide [here](#revoked), or alternatively you can try other download links!

---


Method 1 has a very high success rate and will not erase your data.

Method 2 will definitely work and it will erase your data.

You must not use any backups with Method 2

### Method 1

1. Remove the Config Profile and uninstall every sideloaded app you've installed
2. Back up your device with iTunes or Finder
3. After backing up, restore your device in Recovery Mode or DFU mode.
5. Plug your phone in, go on either Finder for macOS or iTunes for Windows and click on restore backup from your device's menu
6. Now follow the guide again from Installing the Config Profile

### Method 2

1. Remove the Config Profile and uninstall every sideloaded app you've installed
2. Restore your device using Recovery Mode or DFU mode
6. Now follow the guide again from Installing the Config Profile


