# Join this Discord [server](https://discord.gg/rHMa3sMse7) for updates regarding everything!

# THE MADNS IS NOT AVAILABLE CURRENTLY! EVEN THOUGH THE GUIDE REFERS TO IT

# This guide nor the app guides are not finished! Please proceed with caution!

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
If you have any issues, requests or ideas please make an issue here on GitHub or contact me on Discord [here](https://discord.gg/rHMa3sMse7)

## How does this method work?
By using leaked business enterprise certificates, We can sign apps using their credentials which means Apple lets us install the apps without any hassle, however after a while Apple revokes the certificate which can be easily bypassed by using any of the two profiles below,

The madNS Config Profile simply blocks these Apple Servers instead of redirection. This method additionally supports VPNs, ChatGPT and Feather properly.

## Before we start
- This might not work for you if you've been using other enterprise sideloaders as the certificates might be revoked!
- If you are revoked you will need to follow this [guide](#revoked)
- This will work as long as you read and do all of the steps required
- WhySooooFurious = WSF

### Compatibility
This should work for all iOS and iPadOS devices on the latest versions.
The guide is compatible with other sideloading services as long as they rely on enterprise certificates to install.

# Starting the guide!

### Which Config Profile do I choose?
The WSF Config Profile redirects Apple servers to https://localhost.direct (which is your own local network) which prevents Apple from contacting your device about the revoked certificate.
Additionally, the WSF Config profile supports Update Blocking

The madNS Config Profile supports VPNs, Feather and ChatGPT which can be a deciding factor.
Additionally, the madNS Config Profile support Ad-Blocking and Update Blocking

### Part [1/2] Installing the Config Profile
1. Go down to [Downloads](#downloads) and click on the link, then Config Profiles and then select the Config Profile you would like to install
2. Click on Download, and the profile should be imported into settings automatically
3. Now, open settings and go to General > VPN & Device Management and install the downloaded profile
4. It should now automatically be enabled
5. Continue onto [Part 2](#part-22-installing-portal) to install Portal

### Part [2/2] Installing the WSF Portal App
1. Go down to [Downloads](#downloads) and click on the link, then WSF Portal and then select any of the links, keep in mind if none of them install you need to follow this [guide](#revoked)
3. Click on install once the popup comes up
4. Open settings and go to General > VPN & Device Management > (should show the WSF Portal app under the link you picked back in Step 1.)
5. Click on Trust at the top then click on allow, after this your device might need to be restarted
6. If your device was restarted, swipe up and click on install profile
7. WSF Portal should now be on your home screen, fully functional
8. Now read the guides in the app themselves to install your chosen sideloader!

## Troubleshooting
- Unverified?
- Crashing apps?
- Unable to Install?
- App is not available?
- Integrity could not be verified?
You need to follow this [guide](#revoked) or alternatively you can try other download links!
---
## Downloads
### [All Downloads!](https://whysoooofurious.netlify.app/downloads)
               
---
## FAQ
-
Q - Can I use a VPN?
A - You can if you're utilising the madNS Config Profile, guide is in the Portal app
-
Q - Will a restart bypass this and revoke my apps?
A - Some users have found that on older devices, your apps might revoke, enable Airplane Mode and forget Wi-Fi when restarting or shutting down.
-
Q - Will services such as AltStore, Sideloadly and Sidestore affect this guide at all?
A - No, Those listed services use developer signing instead of Enterprise signing so they are fine to use alongside! You will however need to setup the Sideloadly's WireGuard, guide is in the Portal app

### Revoked?
So you've gotten yourself revoked, Follow the methods listed below and you should be unrevoked.

Method 1 will work.

Method 2 will completely reset your device and will definitely work

You must not use your backups with Method 2


#### Method 1
1. Remove the Configuration Profile and uninstall everything you've installed with this method
2. Back up your device, here is a [guide](https://shorturl.at/fnR5J)
3. After backing up, reset your device, here is a [guide](https://shorturl.at/JKnhG), iTunes restore in Recovery Mode or DFU mode is heavily recommended
5. Now if you have an iCloud backup you should be prompted to restore from your backup after logging in to your Apple ID, if you have a local backup all you need to do is plug your phone in, go on either Finder for macOS or iTunes for Windows and click on restore backup from your device's menu
6. Then follow Part 1 of the guide to prevent revokes

#### Method 2
1. Remove the Configuration Profile and uninstall everything you've installed with this method
2. Follow this [guide](https://shorturl.at/JKnhG)
3. Then follow Part 1 of the guide to prevent revokes
