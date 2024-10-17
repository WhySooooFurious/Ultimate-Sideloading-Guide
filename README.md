# Forgot to include the ESign analytic URLS in the denylist step! First thing I get to in the morning! xoxo love y'all.

Disclaimer: This doesn't cost me anything from now on except my time, I'd appreciate if you guys donated but no fucking pressure at all! 

eat my dust apple

[Here](https://shorturl.at/82U3M) is the PayPal donation link! 

I'm *never* going to charge for this at all! Fuck people who do!

## Introduction
Hello, Welcome to my guide on how to sideload on Apple Devices using a method I came across to a while back. This sideloading method has worked for long periods of time, without any app limits and without a pc. I eventually found some small let-downs such as the go-to DNS at the time was and is still made by some random Vietnamese guy with no open-sourced data which naturally has some privacy concerns. ESign also had undesirable analytics which are now blocked by my DNS.

After a few months of using both of these services I decided to reverse-engineer the DNS and how the enterprise signed ESign was downloaded over the web with the click of a button. With enabling better preventions against revokes unlike other people who keep on using other people's DNS and put no effort in themselves with bad instructions to say the least. 

Some of the advantages with using this method
- Free!
- No PC at all!
- On Device Signing!
- No App Limit!
- Easy to setup and use!
- Takes 10 minutes to setup!

The DNS is compatible with other services such as Scarlet, Feather and any other enterprise signing app, More info [here](#scarlet-feather-and-other-sideloaders)

Without further ado, welcome to my Ultimate Sideloading Guide, if you have any issues, requests or ideas please make an issue here on GitHub.

## Scarlet, Feather and other sideloaders
The DNS is compatible with all services as long as they rely on enterprise certificates to install.

Feather is also available to download and the steps should be similar as ESign's

Follow Part 1 and 2 of my guide to install the DNS blocker for these services.

You do not need to follow Part 3, 4 and 5 as these install ESign itself.

## How does this method work?
By using leaked business enterprise certificates, We can sign apps using their credentials which means Apple lets us install the apps without any hassle, however after a while Apple revokes the certificate, this is where the DNS Blocker comes in, the DNS blocker blocks Apple servers from contacting your device about the expired/revoked/blacklisted certificate which in turn lets you use the apps for however long you'd like. The DNS also blocks ESign analytics.

## Before we start
- This will NOT unrevoke your apps! If you need to fix revokes, use this [guide](#revoked-or-blacklisted)
- Make sure you have not been using services such as Scarlet and Feather before as the certificates used to install ESign on your device might be revoked! 
- If you are blacklisted or revoked from Apple for already using services such as Scarlet and Feather you will need to follow this [guide](#revoked-or-blacklisted)
- This method will work as long as you read and do all of the steps required

## Compatibility
This should work for all iOS, iPadOS and even macOS devices, on the latest versions of all iOS, iPadOS and macOS.

Beta versions will work but *may* become revoked around the 1 week mark. It is better to be on a release version!

Versions that might not be supported are below iOS 12, iPadOS 13 and macOS 11.

## Part [1/5] Making your DNS!
1. Go to this [website](https://shorturl.at/hfr4V) and make your own account
2. Go to the Denylist tab and add the following domains:
   
   vpp.itunes.apple.com
   
   appattest.apple.com
   
   certs.apple.com
   
   crl.apple.com
   
   valid.apple.com
   
   ocsp2.apple.com
   
   ocsp.apple.com
   
3. Go to the Allowlist and add the following domain:
   
   app.localhost.direct
4. Continue onto [Part 2](#part-25-installing-the-dns) to finish the DNS installation

## Part [2/5] Installing the DNS
1. Go to the Setup tab, find and click on the hyperlinked apple.nextdns.io which should redirect you to the NextDNS Profile website
2. Select the profile you edited
3. Enable the Trust NextDNS Root CA and Bootstrap IPs toggle
4. Click on Download, and the profile should be imported into settings automatically
5. Now, open settings and go to General > VPN & Device Management and install the downloaded profile
6. The DNS should now automatically be enabled, Do not change the DNS settings to automatic otherwise your apps will get revoked!
7. Now, go back and then go to General > About > Certificate Trust Settings
8. Enable Full Trust for the NextDNS Root Certificate, if Full Trust does not show you cannot use VPNs at all
9. Continue onto [Part 3](#part-35-installing-esign) if you want to install ESign

## Part [3/5] Installing ESign
1. Go down to [Downloads](#downloads) and click on ESign Direct Install
2. Click on install once the popup comes up
3. Open settings and go to General > VPN & Device Management > HDFC Life Insurance Company Limited
4. Click on Trust at the top then click on allow, after this your device might need to be restarted
5. If your device was restarted, swipe up and click on install profile
6. ESign should now be on your home screen, fully functional
7. Continue onto [Part 4](#part-45-setting-up-esign) to setup ESign
 
## Part [4/5] Setting up ESign
1. Open ESign and accept the agreements
2. Go into Settings and click on Get Device UDID
3. Select allow and then you should be redirected to settings
4. After opening settings go to General > VPN & Device Management
5. Install the Query Device UDID profile
6. You should be redirected back to ESign
7. Now go down to [Downloads](#downloads) and click on Certificate and then select any file to download
9. Go into ESign Settings and click on Import Resources
10. Find and select the certificate you downloaded back in Step 7 and click on Import
11. Now go over to AppStore in ESign and click on App Source
12. Click on the plus icon and paste in the sources from [here](#esign-sources), click on add all
13. You now have setup ESign with all sources ready to install apps
14. Continue onto [Part 5](#part-55-using-esign)

## Part [5/5] Using ESign
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
15. Now read the [Post Install Notes](#post-install-notes)

## Post Install Notes
- You must never disable the DNS
- Don't exit ESign while the app is being signed!
- Don't install a lot of apps at once!
- Don't install Safari extensions
- Don't use Cowabunga Lite otherwise the DNS will disappear! There is a workaround, i'll make a guide soon
- Don't use Nugget otherwise the DNS will disappear! There is a workaround, i'll make a guide soon

Not following the above will make your apps revoked!

## Downloads
[ESign Install](https://shorturl.at/R6bNv)

[Feather Install](https://shorturl.at/xTb4K)

[Certificates](https://shorturl.at/4Zdn4)

## Questions/Answers

Q - Won't a VPN bypass the DNS and revoke my apps?

A - It shouldn't , based on the settings I used, I do not recommend using a VPN. If you really want to use a VPN, Use this [guide](#using-a-vpn)

---

Q - Will a restart bypass the DNS and revoke my apps?

A - Simple answer, No.

---

Q - Um, I'm a cocky big-time dev and I need to look at your code thingies to ensure they don't have viruses.

A - Sure, Go over [here](https://shorturl.at/zHEbJ) to look at what is used in the process!

---

# Miscellaneous Guides

## Using a VPN 
So you want to use a VPN with the DNS blocker, follow the steps below and you should be able to use your VPN normally and on-demand, I still do not recommend using a VPN with the DNS, You should know how to configure your VPN's DNS server yourself as there are different steps for each VPN app.

### Method 1
1. 45.90.28.51 and 45.90.30.51 are the DNS servers you need to replace in your VPN's settings

## Revoked? or Blacklisted?
So you've gotten yourself blacklisted, either from the DNS (which seems very unlikely) or from another creator's DNS. Follow the methods listed below and you should be unrevoked. 

Use Method 2 if Method 1 does not work.

You must not use your backups with Method 2 otherwise you will get revoked again.

### Method 1
1. Back up your device, here is a [guide](https://shorturl.at/fnR5J)
2. After backing up, reset your device, here is a [guide](https://shorturl.at/JKnhG)
3. Now if you have an iCloud backup you should be prompted to restore from your backup after logging in to your Apple ID, if you have a local backup all you need to do is plug your phone in, go on either Finder for macOS or iTunes for Windows and click on restore backup from your device's menu
4. Then follow Part 1 and 2 of the guide to prevent revokes in the future

### Method 2
1. Follow this [guide](https://shorturl.at/JKnhG)
2. Then follow Part 1 and 2 of the guide to prevent revokes in the future

## ESign Sources
My sources for ESign                    
###
    source[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]

## Tips & Tricks for ESign
Making use of ESign settings!

### Adding sources
Adding sources to ESign
1. Either copy a link that looks like the one above, or copy a link, note that not all links are compatible with ESign
2. Go to the AppStore tab in ESign
3. Click on App Source on the top left
4. Click the plus button on the top right
5. ESign should prompt you to paste the contents in, if not, copy in the prompt and click on add

### Exporting sources
Export selected sources from ESign.
1.  Go to the AppStore tab in ESign
2. Click on App Source on the top left
3.  Click the Select button on the bottom right
4. Select which sources you want and then click share

### Deleting sources
This will delete selected sources from ESign.
1. Go to the AppStore tab in ESign
2. Click on App Source on the top left
3. Click the Select button on the bottom right
4. Select which sources you want and then click on delete

### Enabling Auto Import
When an app is downloaded, ESign will automatically import your files into your app library.
1. Go into the Download tab
2. Click on the 3 dots on to top left corner
3. Click on settings
4. Enable Auto Import

### Enabling Auto Delete
When an app is downloaded, ESign will automatically delete the app, recommended use with Auto Import.
1. Go into the Download tab
2. Click on the 3 dots on to top left corner
3. Click on settings
4. Enable Auto Delete

### Default Sign Config
This will let you pick a predefined config for your apps.
1. Go onto the Settings Tab
2. Click on Sign Default Config
3. Change the settings as desired

### Keep Running in Background
Let ESign run in the background (won't work while signing an app) and keep ESign vertical
1. Go onto the Settings Tab
2. Enable Keep Running in Background

### Lock Vertical
Keep ESign vertical.
1. Go onto the Settings Tab
2. Enable Lock Vertical

### Change Theme
Change the ESign theme and icon, you can change the icon only when using with Altstore.
1. Go onto the Settings Tab
2. Click on Theme
3. Change the settings as desired
