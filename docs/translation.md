# Translation for Portal's Guides

Please read this guide carefully and follow all instructions precisely

For efficiency, use a PC or Laptop

Additionally you can use tools like VSCode to make this easier, I myself just use XCode or TextEdit

## What You **Cannot** Do
- Do not remove or alter `#`, `##`, or `###`
- Do not remove `(accent://)` or the `[ ]` in titles.
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
  - Any Certificate names
  - And any others if you feel the need to after consulting me

If you have any questions or notice missing information, please reach out in `#contributor-chat` for assistance

---

## Part 1 of 2: Setting Everything Up

1. **Download Guides:**
   - Download the `.zip` file from [GitHub](https://github.com/WhySooooFurious/Ultimate-Sideloading-Guide/archive/refs/heads/main.zip)

2. **Extract Folder:**
   - Keep the `wsf-app-guides` folder and delete the others

3. **Locate Guides:**
   - Navigate to the `en` folder to find all necessary guides to be translated, do not translate from other languages

4. **Translate Maintainer Information:**
   - Open `maintainer_information.md`.
     
     Here you'll have a bit of a snippet of how you should translate, with an example down below in Spanish

   - **Translate the following:**
   
     ```markdown
     ## [Maintainer Information](accent://)

     Information about who is currently maintaining this language.

     ### [Maintained By](accent://)

     (your_name_or_username_here)

     All information here is maintained by a translator and may not be accurate or up to date.

     If you require help, join the [Discord Server](https://discord.gg/wsf)
     ```
    
     ```markdown
     ## [Información del mantenedor](accent://)

     Información sobre quién mantiene actualmente este idioma.

     ### [Mantenido por](accent://)

     Jimmy

     Toda la información aquí es mantenida por un traductor y puede no ser precisa o no estar actualizada.

     Si necesitas ayuda, únete al [Discord Server](https://discord.gg/wsf)
     ```

     See how I changed the text without changing any special characters, kept the spacing and important English words such as Discord Server the same?
     This is a example of a good translation.

5. **Save File:**
   - Save your translated file. Congratulations, you have successfully translated a file!

---

## Part 2 of 2: Translating and Editing `Markdown_filenames.plist`

1. **Translate all Other `.md` Files:**
   - Proceed to translate the rest of the `.md` files, adhering to the guidelines above.

2. Now after you have translated every other .md, you need to edit it's title name, do this for every other .md as well, with an example down below in Spanish
   
   **Edit `Markdown_filenames.plist`:**
   - Open `Markdown_filenames.plist`.
   - **Only translate the `Maintainer Information` in this case.**
   
   - Do not modify any other parameters to prevent Portal from malfunctioning.
   
   - Do NOT change the key lines at all!
     
   - **Example:**
     ```xml
     <dict>
         <key>file_title</key>
         <string>Maintainer Information</string> (YOU EDIT ONLY THIS LINE)
         <key>file_name</key>
         <string>maintainer_information.md</string>
     </dict>
     ```
     
     Do this for all other titles

4. **Review Your Work:**
   - Double-check all files for spelling, grammar, punctuation, and spacing errors

5. **Submit Translations:**
   - Zip up your files if you can and submit them on Discord directly

6. **Team Review:**
   - The WSF Team will review your submission, Thank You for taking a part in helping Portal become better!
