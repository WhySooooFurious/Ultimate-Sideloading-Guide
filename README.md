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

- Compatible with ESign/Feather/GBox/Scarlet

## How does this method work?

By using enterprise certificates, We can sign apps using enterprise credentials which means Apple lets us install the apps without any hassle, however after a while Apple revokes the certificate which can be easily bypassed by using this method.

We have made our own app called Portal and it contains everything you'll ever need for sideloading, and additionally has all links to ESign, Feather, GBox and Scarlet inside the app itself!

## Unsupported Methods

We don't support other guides that use services such as NextDNS as those have limits, and apps will revoke if you pass that limit.

They will also not have the required information on how to use Portal and are not accurate.

The madNS Config Profile itself does use NextDNS and is transparent as we could make it. It is run for by donators and will keep running for as long as possible.

## Before we start

- This might not work for you if you've been using other enterprise sideloaders!

- This should work for all iOS and iPadOS devices on latest iOS versions, won't work for iOS 15 and below.

- This will work as long as you read and do all of the steps properly!


## Privacy

You can view the privacy report [here](https://nch.pl/s/rKBAY59pNcX5bpJ/download?path=%2F&files=maDNS%20Config%20Profile%20Privacy%20Report.pdf&downloadStartSecret=5en4k2r6yuv)

If you still have privacy concerns about the madNS Config Profile, make an issue on github with your email and i'll send you a viewing invite so you can see the settings for yourself.

Make sure to mention exactly what the madNS's profile name is so I can give it to you!

If you STILL have privacy concerns, use the WSF Config Profile, it uses a native iOS Configuration Profile method to redirect Apple Certificate Servers to https://localhost.direct, making sure it will never reach Apple and revoke your apps!

## FAQ

---

Q - Can I use a VPN?

A - You can if you're utilising the madNS Config Profile, make sure to set it up first! VPN Guide is in the Portal app and Discord!

---

Q - Will a restart bypass this and revoke my apps?

A - Disable Wi-Fi and enable Airplane Mode when wanting to restart or shutdown.

---

Q - Will services such as AltStore, Sideloadly and Sidestore affect this guide at all?

A - No, You will however need to setup the Sideloadly's WireGuard using the VPN Guide which is in the Portal app and Discord.

---

# Main Guide!

## Which Config Profile do I choose?

### WSF Config Profile

Pros:

- Privacy Oriented.

- Generally more stable.

Cons:

- No VPN, Feather or ChatGPT support


### madNS Config Profile

Pros:

- Supports VPNs, Feather and ChatGPT.

- Privacy oriented as can be.

Cons:

- None.

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

1. Go down to [Downloads](#downloads) and click on the link, then Portal and then select any of the links, keep in mind if none of them install you need to follow this [guide](#fixing-revokes)
  
2. Click on install once the popup comes up

3. Open settings and go to General > VPN & Device Management > (should show the Portal app under the certificate you picked back in Step 1)

4. Click on Trust at the top then click on allow, after this your device might need to be restarted

5. If your device was restarted, swipe up and click on install profile

6. Portal should now be on your home screen, fully functional

7. Now read the guides in Portal to install your chosen sideloader!

8. Enjoy sideloading apps

## Downloads

Download Link is in the #links channel in the Discord [Server](https://discord.gg/kwvwkCBhxT)

## Troublshooting

- Unverified?

- Crashing Apps? 

- App is not available? 

- Integrity could not be verified? 

You need to follow the Revoked Guide [here](#revoked), or alternatively you can try other download links!

---

## Fixing Revokes

Method 1 has a very high success rate and requires a computer

Method 2 has a very low success rate and doesn't require a computer

Method 3 will definitely work, requires a computer and it will erase your data.

You must not use any backups with Method 3

### Method 1

1. Remove the Config Profile and uninstall every app you've installed
  
2. Back up your device with iTunes or Finder
  
3. After backing up, restore your device in DFU mode
  
4. Then all you need to do is plug your phone in, go on either Finder for macOS or iTunes for Windows and click on restore backup from your device's menu
  
5. Now, follow the guide again from Installing the Config Profile
   
### Method 2

1. Remove the Config Profile and uninstall every app you've installed

2. Back up your device using iCloud

3. Reset your device from Settings > General > Transfer or Reset iPhone > Erase All Content and Settings

4. Restore your iCloud backup when it is successful

5. Now, follow the guide from Installing the Config Profile

### Method 3

1. Remove the Config Profile and uninstall every app you've installed

2. Restore your device using DFU mode in iTunes or Finder

3. Now, follow the guide from Installing the Config Profile
