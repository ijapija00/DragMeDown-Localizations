**DragMeDown (iOS 10)**

This is an open repository where you can contribute with language packs for DragMeDown. Please follow the instructions down below and make a pull request.

**Instructions:**
 1. Clone the repository and clone the 'en-US.lproj' to a new folder. Rename it to match your language, English (US) will become 'en-US'. Make sure the folder extension is '.lproj', which means that English (US) should be renamed this way: en-US.lproj.
 2. Translate everything in Localizable.strings to match your language.
 3. Open Info.plist and change all keys. The keys 'LanguagePackVersion' and 'LanguagePackBuild' is the version details, so make sure to update them in one or another way.
 4. Make a Pull Request. If everything's fine, DragMeDown will soon tell all users that the language is available to download.

**How does the update feature work?**

Pretty Simple! There is a payload online that will be downloaded by DragMeDown's Language Controller. On all devices, there is a BuildManifest containing the same information. If the Build Version is newer online, there is something new in the language pack, and it will show an update window.

**Why not implementing everything inside the DEB-file?**

I don't have enough time to publish minor versions including new lanuage packages. Instead, everything is handled by DragMeDown. Also, people will receive new language packs so much faster.

