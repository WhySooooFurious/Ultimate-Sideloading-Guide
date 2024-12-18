# This is a guide on how to translate Portal's Guides.
Be sure to read this carefully and fully without error.

I recommend you use a PC or Laptop as this will be seriously inefficient to do on a phone.

What you CANNOT do:
- Do NOT remove/change any # or ## or ###
- Do NOT remove the (accent://)
- Do NOT remove the [ or ] in a title
- Do NOT change the meaning of any text
- Do NOT change filenames at all
- Do NOT remove titles or descriptions
- Do NOT remove any text even if it seems useless to you
- Do NOT remove or take out spacing in between steps
- Do NOT add your own information

What you CAN do
- You HAVE to be precise and accurate in your translation
- You CAN switch up punctuation, grammar and some words to make it easier for your language to keep the meaning
- You CAN change titles

Notes:
- Do NOT translate the contents of certificates_information.md, you CAN translate the title only.
- Should be obvious but do NOT translate something like "madNS Config Profile," it helps us during troubleshooting
- You HAVE to keep some English words the same, for example:
  - Discord
  - Portal
  - Revoked
  - Certs or Certificates

If anything important is missing, or you have a question, message in #contributor-chat for help


# Part [1/2] Setting everything up

1. Make sure you've downloaded the guides themselves, download the .zip from [here](https://github.com/WhySooooFurious/Ultimate-Sideloading-Guide/archive/refs/heads/main.zip)

2. The folder you will need is the wsf-app-guides, you can delete the others

3. Go into the "en" folder and you'll see all the guides you will need.

4. Open up maintainer_information.md and TRANSLATE the following into your language as described down below.

## [Maintainer Information](accent://)

Maintained by (put_your_name_or_username_here)

All information here is maintained by a translator and may not be accurate or up to date.

If you require help, join the [Discord Server](https://discord.gg/wsf)

5. Save the file, congrats, you translated a file!

# Part [2/2] Translating and additionally editing Markdown_filenames.plist

1. You should now go on and translate other .md files, make SURE to keep in mind of the Do's and Don'ts.

2. Now, open up Markdown_filenames.plist

3. Here you can only translate: <string>Maintainer Notes</string>
   as shown below. Do NOT touch anything else otherwise Portal will be stuck in a loop.

	<dict>
		<key>file_title</key>
		<string>Maintainer Notes</string>
		<key>file_name</key>
		<string>maintainer_notes.md</string>
	</dict>

4. After translation, be SURE to check your double check your files for any spelling errors, grammar or punctuation errors and general errors such as spacing

5. You should now give us the files, preferably in a compressed format.

6. We will check the files ourselves and see if you have followed steps correctly!

7. The whole WSF Team thanks you for your efforts whole heartedly and appreciates your efforts to make Portal great!

   