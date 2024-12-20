# Translation Guide for Portal's Guides

Please read this guide carefully and follow all instructions precisely. For efficiency, use a PC or laptop instead of a phone.

Additionally you can use tools like VSCode to make this easier, I myself just use the XCode or TextEdit for small changes.

## What You **Cannot** Do
- **Headings:** Do not remove or alter `#`, `##`, or `###`.
- **Special Text:** Do not remove `(accent://)` or the `[ ]` in titles.
- **Special Formatting :** Do not remove "`"
- **Content Integrity:** Do not change the meaning, filenames, titles, descriptions, or any text, even if it seems unnecessary.
- **Formatting:** Do not remove or alter spacing between steps.
- **Additions:** Do not add your own information.

## What You **Can** Do
- **Translation:** Translate accurately and precisely.
- **Language Adjustment:** Adjust punctuation, grammar, and some words for clarity in your language.
- **Titles:** You may translate titles

## Additional Notes
- **Technical Terms:** Do not translate terms like "madNS Config Profile" to aid troubleshooting.
- **Keep Certain English Terms Unchanged:**
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
 
  - And any others if you feel the need to after consulting me.

If you have any questions or notice missing information, please reach out in `#contributor-chat` for assistance.

---

## Part 1 of 2: Setting Everything Up

1. **Download Guides:**
   - Download the `.zip` file from [GitHub](https://github.com/WhySooooFurious/Ultimate-Sideloading-Guide/archive/refs/heads/main.zip).

2. **Extract Folder:**
   - Keep the `wsf-app-guides` folder and delete the others.

3. **Locate Guides:**
   - Navigate to the `en` folder to find all necessary guides to be translated

4. **Translate Maintainer Information:**
   - Open `maintainer_information.md`.
   - Translate the content into your language, ensuring accuracy.
   - **Translate the following:**
     ```markdown
     ## [Maintainer Information](accent://)

     Maintained by (your_name_or_username_here) (social links are accepted)

     All information here is maintained by a translator and may not be accurate or up to date.

     If you require help, join the [Discord Server](https://discord.gg/wsf)
     ```

5. **Save File:**
   - Save your translated file. Congratulations, you have successfully translated a file!

---

## Part 2 of 2: Translating and Editing `Markdown_filenames.plist`

1. **Translate all Other `.md` Files:**
   - Proceed to translate the remaining `.md` files, adhering to the guidelines above.

2. Now after translating every other .md, you need to edit it's title name, do the following for every other .md as well
   **Edit `Markdown_filenames.plist`:**
   - Open `Markdown_filenames.plist`.
   - **Only translate the `Maintainer Information` in this case.** Do not modify any other parameters to prevent Portal from malfunctioning. Do NOT change the key lines at all!
   - **Example:**
     ```xml
     <dict>
         <key>file_title</key>
         <string>Maintainer Information</string> (YOU EDIT ONLY THIS LINE)
         <key>file_name</key>
         <string>maintainer_information.md</string>
     </dict>
     ```
     do this for all other files as well, the above is an example

3. **Review Your Work:**
   - Double-check all files for spelling, grammar, punctuation, and spacing errors.

4. **Submit Translations:**
   - Zip up your files if you can and submit them on Discord directly.

5. **Team Review:**
   - The WSF Team will review your submissions to ensure all steps have been followed correctly.

6. **Thank You:**
   - The WSF Team thanks you for your service.

---
