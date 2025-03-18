# Introduction

Welcome to our guide on how to sideload on Apple Devices!

Advantages:

- Free!

- No PC!

- Easy to use!

- No App Limits!

- On Device Signing!

- No Privacy Concerns!

- Takes 5 Minutes to Setup!

- Compatible with ESign/Feather/GBox/Scarlet

## Privacy

You can view the privacy report [here](https://nch.pl/s/rKBAY59pNcX5bpJ/download?path=%2F&files=maDNS%20Config%20Profile%20Privacy%20Report.pdf&downloadStartSecret=5en4k2r6yuv).

If you still have privacy concerns about the madNS Config Profile, make an issue on github with your email and i'll send you a viewing invite so you can see for yourself.

If you still have privacy concerns, use the WSF Config Profile, it uses a native iOS Configuration Profile method to redirect Apple Certificate Servers to https://localhost.direct, which is your own local network.

## Portal

We have our very own app called Portal, which includes a signer, download links to sideloaders, guides with a variety of languages, and a functional sources viewer/downloader.

Portal is easy to use, stable and offers a great user experience for everyone.

## FAQ

---

Q - Can I use a VPN?

A - You can if you're utilising the madNS Config Profile, make sure to set it up by using the VPN Guide which is in the Portal app and Discord!

---

Q - Will services such as AltStore, Sideloadly and Sidestore affect this guide at all?

A - No, You will however need to setup the Sideloadly's WireGuard using the VPN Guide which is in the Portal app and Discord.

---

## Tutorials

**Video Guides by TechJunkieAman:**

[AIO Portal + Sideloaders Guide](https://www.youtube.com/watch?v=OysjLfxNu_g)

[ESign Guide](https://www.youtube.com/watch?v=MwKJjGlXni0)

[Feather Guide](https://www.youtube.com/watch?v=8DiBMAdLMiY)

**Video Guides by Erdi:**

[Portal Guide](https://youtu.be/nni_DNix490?feature=shared)

**Interactive Shortcut Guides by Frizzle:**

[AIO Portal + Sideloaders Shortcut Guide](https://routinehub.co/shortcut/21677/)

## Which Config Profile do I choose?

### WSF Config Profile

Pros:

- Privacy Oriented

Cons:

- No VPN, Feather, Apple Relay, Push Notifications or ChatGPT support


### madNS Config Profile

Pros:

- Supports VPNs, Feather, Apple Relay, Push Notifications and ChatGPT

- Privacy Oriented as can be

Cons:

- None

### What does the code mean in the Config Profiles?

UB: Blocks Apple OTA Updates

AB: Blocks Ads and Trackers

EXP: For testing and fixing issues, please don't use this unless requested to, this particular variant DOES log everything you do

Don't use VPNs while installing unless you've set it up using the VPN Setup Guide.

## Installation Guide

### Part [1/2] Installing the Config Profile

1. Go down to [Downloads](#downloads) and click on the link, then Config Profiles and then select the Config Profile you would like to install

2. Click on Download, and the profile should be imported into settings automatically
  
3. Now, open settings and go to General > VPN & Device Management and install the downloaded profile
  
4. Continue onto [Part 2](#part-22-installing-portal) to install Portal

### Part [2/2] Installing Portal

1. Go down to [Downloads](#downloads) and click on the link, then Portal and then select any of the links, keep in mind if none of them install you need to follow this [guide](#fixing-revokes)
  
2. Click on install once the popup comes up

3. Open settings and go to General > VPN & Device Management > Certificate you selected

4. Click on Trust at the top then click on allow, after this your device might need to be restarted

5. If your device was restarted, swipe up and click on install profile

6. Now, open Portal and continue the installation

## Downloads

Download Link is in the #links channel in the Discord [Server](https://wsfteam.xyz/discord)

## Troubleshooting

- Unverified?

- Crashing Apps? 

- App is not available? 

- Integrity could not be verified? 

Try other downloads links, if they don't work, then follow this [guide](#fixing-revokes).

---

## Fixing Revokes

Method 1 has a low success rate and doesn't require a computer

Method 2 has a medium-high success rate and requires a computer

Method 3 has a high success rate and requires a computer

Method 4 will work, requires a computer and it will erase your data.

### Method 1

1. Remove the Config Profile and uninstall every sideloaded app you've installed

2. Back up your device using iCloud

3. Reset your device from Settings > General > Transfer or Reset iPhone > Erase All Content and Settings

4. Restore your iCloud backup

5. Now, follow the guide again


### Method 2

1. Remove the Config Profile and uninstall every sideloaded app you've installed
  
2. Put your device in recovery mode and click on update in Finder or iTunes
  
3. Now, follow the guide again

### Method 3

1. Remove the Config Profile and uninstall every sideloaded app you've installed
  
2. Back up your device with iTunes or Finder
  
3. After backing up, restore your device in DFU mode
  
4. Then all you need to do is plug your phone in, go on either Finder or iTunes and click on restore backup from your device's menu
  
5. Now, follow the guide again


### Method 4

1. Restore your device using DFU mode in iTunes or Finder

2. Now, follow the guide again
