## Introduction
Hello, Welcome to my guide on how to sideload on Apple Devices using a method I came across to a while back. This sideloading method has worked for long periods of time, without any app limits and without a pc. I eventually found some small let-downs such as the go-to DNS at the time was and is still made by some random Vietnamese guy with no open-sourced data which naturally has some privacy concerns. ESign also had undesirable analytics which are now blocked by my DNS.

After a few months of using both of these services I decided to reverse-engineer the DNS and how the enterprise signed ESign was downloaded over the web with the click of a button. With enabling better preventions against revokes unlike other people who keep on using other people's DNS and put no effort in themselves with bad instructions to say the least. 

Some of the advantages with using this method
- Free!
- No PC at all!
- On Device Signing!
- No App Limit!
- No privacy concerns
- Easy to setup and use!
- Takes 10 minutes to setup!

The DNS is compatible with other services such as Scarlet, Feather and any other enterprise signing app, More info [here](#scarlet-feather-and-other-sideloaders)

Without further ado, welcome to my Ultimate Sideloading Guide, if you have any issues, requests or ideas please make an issue here on GitHub.

---

## Scarlet, Feather and other sideloaders
The DNS is compatible with all services as long as they rely on enterprise certificates to install.

Feather is also available to download and the steps should be similar as ESign's.

Follow Part 1 and 2 of my guide to install the DNS blocker for these services.

You do not need to follow Part 3, 4 and 5 as these install and setup ESign itself.

---

## How does this method work?
By using leaked business enterprise certificates, We can sign apps using their credentials which means Apple lets us install the apps without any hassle, however after a while Apple revokes the certificate, this is where the DNS Blocker comes in, the DNS blocker blocks Apple servers from contacting your device about the expired/revoked/blacklisted certificate which in turn lets you use the apps for however long you'd like. The DNS also blocks ESign analytics.

---

## Compatibility
This should work for all iOS and iPadOS devices on the latest versions

Beta versions will work but *may* become revoked around the 1-2 week mark. It is better to be on a release version!

Versions that might not be supported are below iOS 12, iPadOS 13

---

## Before we start
- Make sure you have not been using services such as Scarlet and Feather before as the certificates used to install ESign on your device might be revoked!
- If you are blacklisted or revoked from Apple for already using services such as Scarlet and Feather you will need to follow this [guide](#revoked)
- This method will work as long as you read and do all of the steps required

---
