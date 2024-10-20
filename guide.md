## Part [1/5] Making your DNS
1. Go to this [website](https://shorturl.at/hfr4V) and make your own account
2. Go to the Denylist tab and add the following domains:
   If you would also like to block ESign analytics, please use this [guide](#blocking-esign-analytics)
   
   vpp.itunes.apple.com
   
   appattest.apple.com
   
   certs.apple.com
   
   crl.apple.com
   
   valid.apple.com
   
   ocsp2.apple.com
   
   ocsp.apple.com

3. Go to the Allowlist tab and add the following domain:
   
   app.localhost.direct

4. Then go into the Parental Control tab and toggle Block Bypass Methods on
   
5. Continue onto [Part 2](#part-25-installing-the-dns) to finish the DNS installation

## Part [2/5] Installing the DNS
1. Go to the Setup tab, find and click on the hyperlinked apple.nextdns.io which should redirect you to the NextDNS Profile website
2. Select the profile you edited
3. Click on More Options
4. Then Enable the Trust NextDNS Root CA and Bootstrap IPs toggle
5. Click on Download, and the profile should be imported into settings automatically
6. Now, open settings and go to General > VPN & Device Management and install the downloaded profile
7. The DNS should now automatically be enabled, Do not change the DNS settings to automatic otherwise your apps will get revoked!
8. Now, go back and then go to General > About > Certificate Trust Settings
9. Enable Full Trust for the NextDNS Root Certificate, if Full Trust does not show you cannot use VPNs at all
10. Continue onto [Part 3](#part-35-installing-esign) if you want to install ESign

## Part [3/5] Installing ESign
1. Go down to [Downloads](#downloads) and click on the link, then click on ESign and choose any link
2. Click on install once the popup comes up
3. Open settings and go to General > VPN & Device Management > (should show the ESign app under the link you picked back in Step 1.)
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
7. Now go down to [Downloads](#downloads), click the link and then go into certificates, download the ESign certificates, and the Certificates should be downloaded
8. Extract the ESign-Certificates.zip and select the one that corresponds to the ESign app in VPN & Device Management
9. Go into ESign Settings and click on Import Resources
10. Find and select the certificate you selected back in Step 8 and click on Import
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
- You must never disable the DNS!
- Don't exit ESign while the app is being signed!
- Don't install a lot of apps at once!
- Don't install Safari extensions!
- Don't use Cowabunga Lite otherwise the DNS will disappear! There is a workaround, i'll make a guide soon!
- Don't use Nugget otherwise the DNS will disappear! There is a workaround, i'll make a guide soon!
- NextDNS has a limit of 300000 queries per month! I recommend heavily that you do not share your profile as you might reach this limit, I also recommend that you make 2 or more accounts with NextDNS and switch *if* your monthly quota is met for 1 of those profiles!

Not following the above guidelines will make your apps revoked!
