# Ritsu x Emerald

A small project to make Emerald Chat less bad.

Table of Contents:
1. [Installation](#installation)
2. [Features](#features)
3. [Privacy](#privacy)

## Installation

You will need to have a userscript manager installed in your browser.

Popular ones are:
- [ViolentMonkey](https://violentmonkey.github.io/)
- [TamperMonkey](https://www.tampermonkey.net/)

To use RxE on mobile, choose one of the following options:
- **Android**: Firefox Nightly ([Google Play Store](https://play.google.com/store/apps/details?id=org.mozilla.fenix), [YouTube Tutorial](https://youtu.be/GXcg8r0c-Lk?t=232), [Blog Post](https://blog.mozilla.org/addons/2020/09/29/expanded-extension-support-in-firefox-for-android-nightly/))
- **Android**: Kiwi Browser ([Google Play Store](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser)) - Chromium-based browser with Chrome extension support and extra features 
- **iOS**: Userscripts for Safari ([App Store](https://apps.apple.com/us/app/userscripts/id1463298887))
- **iOS**: Gear Browser ([App Store](https://apps.apple.com/us/app/gear-browser/id1458962238))
- **iOS**: Tampermonkey for Safari ([App Store](https://apps.apple.com/us/app/tampermonkey/id1482490089?mt=12), $1.99)

Once that's done, you can [click here to install the latest RxE script](https://raw.githubusercontent.com/Ritsu-Projects/Public-Releases/main/ritsu-emerald.user.js). 
Alternatively, use the scripts in the repository to load a specific version (you will need to click on the <kbd>Raw</kbd> button). If your userscript manager doesn't prompt you to install the script, download it from the link and add it manually (for Tampermonkey, that's Utilities -> File -> Import).
**Warning: Never install scripts from untrusted sources.**

## Features

- **Settings — Ritsu Menu**
  - 3 themes
  - Ad-blocking
  - Anti-spam
  - Custom name colour
  - Customizable chat layout
  - Karma tracking
  - Extra user info
- **Images**
  - <s>Image sending¹</s> *Image servers no longer available*
  - Option to blur images
- **Fixes**
  - Broken DMs
  - Crashed GC
  - Chat stays muted


- **Coming soon** (v11.0):
  - Profile pictures¹
  - Permanent muting
  - Blocking friend requests
  - Highlighted name mentions
  - Clickable links
  - [Material Icons](https://fonts.google.com/icons?selected=Material+Icons)¹ (using `m:icon_name:`)

¹ - between RxE users

## Privacy

RxE stores your RxE settings in your browser. RxE also sends data on your behalf to EmeraldChat when including your profile picture in your bio (v11.0+).
