# Please use this [website](https://whysoooofurious.netlify.app)

## Updates

Won't be working for now.

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

### Part [1/2] Installing the Configuration Profile
1. Go down to [Downloads](#downloads) and click on the link, then Configuration Profiles and then select the Configuration Profile you would like to install, the Update Blocker blocks iOS updates as well
2. Click on Download, and the profile should be imported into settings automatically
3. Now, open settings and go to General > VPN & Device Management and install the downloaded profile
4. It should now automatically be enabled
5. Continue onto [Part 2](#part-22-installing-portal) to install Portal

## Troubleshooting

### Issues Installing
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

A - You can if you're utilising the madNS Configuration Profile, guide is in the Portal app

-

Q - Will a restart bypass this and revoke my apps?

A - Some users have found that on older devices, your apps might revoke, enable Airplane Mode and forget Wi-Fi when restarting or shutting down.

-

Q - Will services such as AltStore, Sideloadly and Sidestore affect this guide at all?

A - No, Those listed services use developer signing instead of Enterprise signing so they are fine to use alongside! You will however need to setup the Sideloadly's WireGuard, guide is in the Portal app
