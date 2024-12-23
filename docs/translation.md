# Translation Guide for Portal

Please read this guide carefully and follow all instructions properly

For efficiency, use a PC or Laptop

Additionally you can use tools like VSCode, XCode, Notepad++, Notepad and TextEdit

I myself use XCode and TextEdit

## What You **Cannot** Do
- Do not remove or alter `#`, `##`, or `###`
- Do not remove `(accent://)` or the `[ ]` in titles
- Do not remove "`"
- Do not change the meaning of any text
- Do not remove spacing between steps and lines of text
- Do not add your own information
- Do not add additional steps

## What You **Can** Do
- Translate accurately and precisely
- Adjust punctuation, grammar, and some words for clarity in your language
- You may translate titles
- You may change text inside `[ ]`
- You may change text after `#" or '##' or '###'

## Additional Notes
- Do not translate terms like "madNS Config Profile" to aid us in troubleshooting
  
- Keep Certain English Terms Unchanged:
  - Discord
  - Portal
  - Revoked
  - Certs or Certificates
  - ESign
  - Feather
  - GBox
  - Scarlet
  - Sources
  - Post Install Notes
  - DNS Servers
  - WSF Config Profile
  - WSF Config Profile + Update Blocker
  - madNS Config Profile + Update Blocker
  - madNS Config Profile + Update Blocker + Ad-Blocker
  - madNS Config Profile + Ad-Blocker
  - madNS Config Profile
  - DNS over HTTPS
  - DNS Servers
  - Any Certificate names
  - Any iOS Terms such as General, VPN and Device Management, Files etc
    
  - And any others if you feel the need to after consulting me

If you have any questions or notice missing information, please reach out in `#contributor-chat` for assistance

---

## Part [1/2]

1. **Download Guides:**
   - Download the `.zip` file from [GitHub](https://github.com/WhySooooFurious/Ultimate-Sideloading-Guide/archive/refs/heads/main.zip)

2. **Extract Folder:**
   - Extract the .zip
   - Navigate to the folder and then go into `wsf-app-guides` and then the `en` folder to find all necessary guides to be translated
   - Delete other folders
     
3. **Translating**
   - Open `maintainer_information.md`.
   - Keep in mind that `maintainer_information.md` is the only one you should replace the text with down below
   - All other .mds you can translate directly
     
     Here you'll have a bit of a snippet of how you should translate, there is an example down below in Spanish
     
   
     ```xml
     ## [Maintainer Information](accent://)

     Information about who is currently maintaining this language.

     ### [Maintained By](accent://)

     (your_name_or_username_here_social_links_are_also_accepted)

     All information here is maintained by a translator and may not be accurate or up to date.

     If you require help, join the [Discord Server](https://discord.gg/wsf)
     ```
    
     ```xml
     ## [Información del mantenedor](accent://)

     Información sobre quién mantiene actualmente este idioma.

     ### [Mantenido por](accent://)

     Jimmy

     Toda la información aquí es mantenida por un traductor y puede no ser precisa o no estar actualizada.

     Si necesitas ayuda, únete al [Discord Server](https://discord.gg/wsf)
     ```

     See how I changed the text without changing any special characters, kept the spacing and important English words such as Discord Server the same?
     
     This is a example of a good translation.

5. **Saving**
   - Save your translated file
   - Congratulations, you have successfully translated a file!
     
6. **More Transation**
   - Translate all other .md files!

---

## Part [2/2]

1. **Changing Titles**
   
   - Now after you have translated every other .md, you need to edit it's title name in  `Markdown_filenames.plist`
   - Do this for every other .md as well, there is an example down below in Spanish
   
   - Open `Markdown_filenames.plist`
  
   - Translate ONLY the `<string>Maintainer Information</string>` in this case
   - Do NOT change any keys or other strings!
     
     ```xml
     <dict>
         <key>file_title</key>
         <string>Maintainer Information</string>
         <key>file_name</key>
         <string>maintainer_information.md</string>
     </dict>
     ```
     ```xml
     <dict>
         <key>file_title</key>
         <string>Información del mantenedor</string>
         <key>file_name</key>
         <string>maintainer_information.md</string>
     </dict>
     ```
     
     This is a example of a good translation
    
     Do this for all other .md titles in `Markdown_filenames.plist`

2. **Double-Check Files**
   
   - Double-Check all files for spelling, grammar, punctuation, and spacing errors

3. **Send your files**
   
   - Zip up your files if you can and submit them on Discord or GitHub!

4. **The End!**
   
   - The WSF Team will review your submission, Thank You for taking a part in helping Portal become better!
