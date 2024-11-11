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

## Ultimate Sideloading Guide

[English Tutorial] - Outdated(https://www.youtube.com/watch?v=F4GAGYm1aIQ)

[Spanish Tutorial] - Outdated (https://www.youtube.com/watch?v=558O5tu7D1E)

### Which Configuration Profile do I choose?
If you would like a basic blocking server choose the WSF Configuration Profile

The madNS Configuration Profile supports VPNs, Feather and ChatGPT which can be a deciding factor.

### Part [1/4] Installing the Configuration Profile
1. Go down to [Downloads](#downloads) and click on the link, then Configuration Profiles and then select the Configuration Profile you would like to install, the Update Blocker blocks iOS updates as well
2. Click on Download, and the profile should be imported into settings automatically
3. Now, open settings and go to General > VPN & Device Management and install the downloaded profile
4. It should now automatically be enabled, this also installs a Web Clip for easy access to my website
5. Continue onto [Part 2](#part-24-installing-esign) if you want to install ESign

### Part [2/4] Installing ESign
1. Go down to [Downloads](#downloads) and click on the link, then click on Downloads, then ESign and choose any link
3. Click on install once the popup comes up
4. Open settings and go to General > VPN & Device Management > (should show the ESign app under the link you picked back in Step 1.)
5. Click on Trust at the top then click on allow, after this your device might need to be restarted
6. If your device was restarted, swipe up and click on install profile
7. ESign should now be on your home screen, fully functional
8. Continue onto [Part 4](#part-34-setting-up-esign) to setup ESign
 
### Part [3/4] Setting up ESign
1. Open ESign and accept the agreements
2. Go into Settings and click on Get Device UDID
3. Select allow and then you should be redirected to settings
4. After opening settings go to General > VPN & Device Management
5. Install the Query Device UDID profile
6. You should be redirected back to ESign
7. Now go down to [Downloads](#downloads), click the link and then go into certificates, download the certificates, and the Certificates should be downloaded
8. Extract the Certificates.zip and keep in mind the one that corresponds to your ESign app in VPN & Device Management
9. Go into ESign Settings and click on Import Resources
10. Find and select the .p12 file you chose back in Step 8 and click on Import
11. Now go over to AppStore in ESign and click on App Source
12. Click on the plus icon and paste in the sources from [here](#esign-sources), click on add all
13. You now have setup ESign with all sources ready to install apps
14. Continue onto [Part 4](#part-44-using-esign)

### Part [4/4] Using ESign
1. Download any app using the AppStore in ESign or you can import your own .ipa using Import Resource in which case you can skip to step 4
2. Check the download status in the Download tab if downloading from the ESign AppStore
3. Click on the downloaded IPA and select Import App Library
4. Your app should now be visible in the Unsigned Apps tab, select unsigned or signed by selecting the bar on top of ESign
5. Click on the app and select Signature
6. You can change your app and edit it here
7. Select Signature and ESign should sign the app using the certificate you selected before
8. There might be red text saying this certificate is revoked, this is normal! Click on the blue button saying Install, then click Install on the prompt again
9. The app should be on your homescreen now
10. Open settings and go to General > VPN & Device Management
11. Select the app you installed and click on Trust
12. Click on Allow, after this your device might need to be restarted
13. If your device was restarted, swipe up and click on Install Profile
14. The app should now be on your home screen, fully functional
15. Now read the [Post Install Notes](#post-install-notes) carefully

### Post Install Notes
- You cannot use a VPN unless you're using the madNS Configuration Profile
- You must never disable the Configuration Profile!
- Go into Airplane Mode if you're removing the Profile or switching to another
- Don't use Nugget or Cowabunga otherwise the Configuration Profile will disappear! There is a [workaround](#using-nugget-or-cowabunga)
- Restarts can revoke apps on older devices! Put your device in Airplane Mode and turning off WiFi when restarting to be safe!
- Check for updates and announcements periodically on the [discord](https://discord.gg/rHMa3sMse7)

Not following the guidelines above will make your apps revoked!

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
