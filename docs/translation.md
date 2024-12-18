# Translation Guide for Portal's Guides

Please read this guide carefully and follow all instructions precisely. For efficiency, use a PC or laptop instead of a phone.

## What You **Cannot** Do
- **Headings:** Do not remove or alter `#`, `##`, or `###`.
- **Special Text:** Do not remove `(accent://)` or the `[ ]` in titles.
- **Content Integrity:** Do not change the meaning, filenames, titles, descriptions, or any text, even if it seems unnecessary.
- **Formatting:** Do not remove or alter spacing between steps.
- **Additions:** Do not add your own information.

## What You **Can** Do
- **Translation:** Translate accurately and precisely.
- **Language Adjustment:** Adjust punctuation, grammar, and some words for clarity in your language.
- **Titles:** You may change titles as needed.

## Additional Notes
- **Certificates Information:** Only translate the title of `certificates_information.md`; do not translate its contents.
- **Technical Terms:** Do not translate terms like "madNS Config Profile" to aid troubleshooting.
- **Keep Certain English Terms Unchanged:**
  - Discord
  - Portal
  - Revoked
  - Certs or Certificates

If you have any questions or notice missing information, please reach out in `#contributor-chat` for assistance.

---

## Part 1 of 2: Setting Everything Up

1. **Download Guides:**
   - Download the `.zip` file from [GitHub](https://github.com/WhySooooFurious/Ultimate-Sideloading-Guide/archive/refs/heads/main.zip).

2. **Extract Folder:**
   - Keep the `wsf-app-guides` folder and delete the others.

3. **Locate Guides:**
   - Navigate to the `en` folder to find all necessary guides.

4. **Translate Maintainer Information:**
   - Open `maintainer_information.md`.
   - Translate the content into your language, ensuring accuracy.
   - **If you are part of the WSF team, use:**
     ```
     All information here is always accurate and up to date.
     ```
   - **Otherwise, translate the following:**
     ```markdown
     ## [Maintainer Information](accent://)

     Maintained by (your_name_or_username_here)

     All information here is maintained by a translator and may not be accurate or up to date.

     If you require help, join the [Discord Server](https://discord.gg/wsf)
     ```

5. **Save File:**
   - Save your translated file. Congratulations, you have successfully translated a file!

---

## Part 2 of 2: Translating and Editing `Markdown_filenames.plist`

1. **Translate Other `.md` Files:**
   - Proceed to translate the remaining `.md` files, adhering to the guidelines above.

2. **Edit `Markdown_filenames.plist`:**
   - Open `Markdown_filenames.plist`.
   - **Only translate the `<string>Maintainer Notes</string>` line.** Do not modify anything else to prevent Portal from malfunctioning.
   - **Example:**
     ```xml
     <dict>
         <key>file_title</key>
         <string>Maintainer Notes</string>
         <key>file_name</key>
         <string>maintainer_notes.md</string>
     </dict>
     ```

3. **Review Your Work:**
   - Double-check all files for spelling, grammar, punctuation, and spacing errors.

4. **Submit Translations:**
   - Compress your translated files and submit them.

5. **Team Review:**
   - The WSF Team will review your submissions to ensure all steps have been followed correctly.

6. **Thank You:**
   - The entire WSF Team sincerely thanks you for your efforts in enhancing Portal!

---

If you follow these instructions carefully, your translation will contribute significantly to making Portal accessible to a wider audience. Thank you for your dedication!
