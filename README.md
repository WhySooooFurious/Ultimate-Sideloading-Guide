# Please use this [website](https://whysoooofurious.netlify.app)

## Updates
Please join this Discord [server](https://discord.gg/rHMa3sMse7) for updates regarding everything!

We are going to be migrating to our own app, which will automatically be updated remotely for the most part. This means most guides on this main readme.md will be slowly removed.

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
- Compatible with Scarlet/Feather/ESign/GBox/QuickSign

If you have any issues, requests or ideas please make an issue here on GitHub or contact me on Discord [here](https://discord.gg/rHMa3sMse7)

## How does this method work?
By using leaked business enterprise certificates, We can sign apps using their credentials which means Apple lets us install the apps without any hassle, however after a while Apple revokes the certificate which can be easily bypassed any of the two profiles below,

The WhySooooFurious Configuration Profile redirects Apple servers to https://localhost.direct (which is your own local network) which prevents Apple from contacting your device about the revoked certificate.

The madNS Configuration Profile simply blocks these Apple Servers instead of redirection. This method additionally supports VPNs, ChatGPT and Feather properly.

## Before we start
- This might not work for you if you've been using other enterprise sideloaders as the certificates might be revoked!
- If you are revoked you will need to follow this [guide](#revoked)
- This will work as long as you read and do all of the steps required
- WhySooooFurious = WSF

### Compatibility
This should work for all iOS and iPadOS devices on the latest versions.

The guide is compatible with other sideloading services as long as they rely on enterprise certificates to install. They are also available to download, they steps should be similar to ESign's.

# Starting the guide!

### Which Configuration Profile do I choose?
If you would like a basic blocking server choose the WSF Configuration Profile

The madNS Configuration Profile supports VPNs, Feather and ChatGPT which can be a deciding factor.

### Part [1/4] Installing the Configuration Profile
1. Go down to [Downloads](#downloads) and click on the link, then Configuration Profiles and then select the Configuration Profile you would like to install, the Update Blocker blocks iOS updates as well
2. Click on Download, and the profile should be imported into settings automatically
3. Now, open settings and go to General > VPN & Device Management and install the downloaded profile
4. It should now automatically be enabled, this also installs a Web Clip for easy access to my website
5. Continue onto [Part 2](#part-24-installing-portal) to install Portal

## Troubleshooting

### Unable to Install? Integrity could not be verified? App is not available? Crashing Apps? Unverified? Crashing on Start?

You need to follow this [guide](#revoked) or alternatively you can try other download links!

---

## Downloads

### [All Downloads!](https://whysoooofurious.netlify.app/downloads)

---

## ESign Sources
My sources for ESign                    
###

https://esign.yyyue.xyz/app.json
https://raw.githubusercontent.com/vizunchik/AltStoreRus/master/apps.json
https://raw.githubusercontent.com/vizunchik/AltStoreRus/master/apps.json
https://qnblackcat.github.io/AltStore/apps.json
https://randomblock1.com/altstore/apps.json
https://wuxu1.github.io/wuxu-complete-plus.json
https://wuxu1.github.io/wuxu-complete.json
https://ipa.cypwn.xyz/cypwn.json
https://driftywinds.github.io/AltStore/apps.json
https://hann8n.github.io/JackCracks/MovieboxPro.json
https://raw.githubusercontent.com/TheNightmanCodeth/chromium-ios/master/altstore-source.json
https://repo.apptesters.org/
https://aio.yippee.rip/repo.json
https://community-apps.sidestore.io/sidecommunity.json
https://raw.githubusercontent.com/arichornloverALT/arichornloveralt.github.io/main/apps2.json
https://raw.githubusercontent.com/arichornloveralt/arichornloveralt.github.io/main/apps.json
https://raw.githubusercontent.com/lo-cafe/winston-altstore/main/apps.json
https://qingsongqian.github.io/all.html
https://tiny.one/SpotC
https://theodyssey.dev/altstore/odysseysource.json
https://provenance-emu.com/apps.json
https://repo.starfiles.co/
https://ish.app/altstore.json
https://raw.githubusercontent.com/Balackburn/YTLitePlusAltstore/main/apps.json
https://ipa.cypwn.xyz/cypwn_ts.json
https://raw.githubusercontent.com/whoeevee/EeveeSpotify/swift/repo.json
https://altstore.oatmealdome.me/
https://raw.githubusercontent.com/driftywinds/driftywinds.github.io/master/AltStore/apps.json
https://alts.lao.sb
https://xitrix.github.io/iTorrent/AltStore.json
https://driftywinds.github.io/repos/esign.json
https://github.com/khcrysalis/Feather/raw/main/app-repo.json
https://apps.nabzclan.vip/repos/esign.php
https://flyinghead.github.io/flycast-builds/altstore.json
https://altstore.oatmealdome.me
https://alt.crystall1ne.dev
https://apps.nabzclan.vip/repos/altstore.php
https://apps.sidestore.io/
https://repos.yattee.stream/alt/apps.json
https://alt.thatstel.la/

---

## Questions/Answers

-

Q - Can I use a VPN?

A - You can if you're utilising the madNS Configuration Profile, follow this [guide](#using-vpns)

-

Q - Will a restart bypass this and revoke my apps?

A - Some users have found that on older devices, your apps might revoke, enable Airplane Mode and forget Wi-Fi when restarting or shutting down.

-

Q - Will services such as AltStore, Sideloadly and Sidestore affect this guide at all?

A - No, Those listed services use developer signing instead of Enterprise signing so they are fine to use alongside! You will however need to setup the Sideloadly WireGuard by using this [guide](#using-vpns)

-

## Miscellaneous Guides

### Using VPNs
Note that most free VPNs won't let you change DNS settings.

Also note that only the madNS Configuration Profile is compatible with VPNs

#### Method 1
1, Find your VPN's DNS settings and replace them with the following (coming soon)

### Revoked?
So you've gotten yourself revoked, Follow the methods listed below and you should be unrevoked.

Method 1 should work

Method 2 will completely reset your device and will definitely work

You must not use any backups with Method 2

#### Method 1
1. Remove the Configuration Profile and uninstall ESign
2. Back up your device, here is a [guide](https://shorturl.at/fnR5J)
3. After backing up, reset your device, here is a [guide](https://shorturl.at/JKnhG), iTunes restore in Recovery Mode or DFU mode is required
5. Now if you have an iCloud backup you should be prompted to restore from your backup after logging in to your Apple ID, if you have a local backup all you need to do is plug your phone in, go on either Finder for macOS or iTunes for Windows and click on restore backup from your device's menu
6. Then follow Part 1 of the guide to prevent revokes

#### Method 2
1. Remove the Configuration Profile and uninstall ESign
2. Follow this [guide](https://shorturl.at/JKnhG)
3. Then follow Part 1 of the guide to prevent revokes

### Using Nugget or Cowabunga
All Configuration Profiles disappear when using Nugget and Cowabunga. This can easily be bypassed by following the steps below.

### Hall of Fame!

u/Comfortable-Basil-47
For introducing me to the whole method and taking the time to teach me!

@timi2506
For creating wonderful icons for the configuration profile and for making the Nothing testing app!

@TheInterasting
For invaluable help with the Server, Beta Testing and dealing with my insanity!

### Partners

@pollacongafes
For the Spanish tutorial!

@Techjunkie_Aman
For the English tutorial!
