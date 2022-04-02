# Ritsu x Emerald

A small addon to make EmeraldChat less bad.

Table of Contents:
1. [Installation](#installation)
2. [Features](#features)
3. [Privacy](#privacy)

## Installation

You will need to have a userscript manager installed in your browser.

Popular ones are:
- [ViolentMonkey](https://violentmonkey.github.io/)
- [TamperMonkey](https://www.tampermonkey.net/) ([YouTube Tutorial](https://www.youtube.com/watch?v=8tyjJD65zws))

To use RxE on mobile, choose one of the following options: 
- **Android**: Kiwi Browser 
([Google Play Store](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser)) - 
Chromium-based browser with Chrome extension support and extra features. 
Install your userscript manager from the Chrome Webstore and proceed as normal.
- __**Android**: Bromite ([Website](https://www.bromite.org/), [F-Droid Repo](https://www.bromite.org/fdroid)) - 
Privacy-focused Chromium-based browser with userscript support. 
No extension needed to use RxE, userscripts can be added in the settings. 
Download and open the `.apk` file to install Bromite. 
Alternatively, download the F-Droid store for open-source Android apps, 
and add the Bromite repository to receive automatic updates.__ — Does not seem to work as-is, may require adjustments from our side.
- **Android**: Firefox Nightly 
([Google Play Store](https://play.google.com/store/apps/details?id=org.mozilla.fenix), 
[YouTube Tutorial](https://youtu.be/GXcg8r0c-Lk?t=232), 
[Blog Post](https://blog.mozilla.org/addons/2020/09/29/expanded-extension-support-in-firefox-for-android-nightly/)) - 
Bleeding edge version of Firefox for Android. 
On PC, create an add-on collection on [addons.mozilla.org](https://addons.mozilla.org), and add your userscript manager to the collection. 
On Android, unlock Firefox Nightly's developer options by tapping the About Menu's logo, 
and then input your User ID & collection from the URL as the custom addon collection.
- **iOS**: Gear Browser ([App Store](https://apps.apple.com/us/app/gear-browser/id1458962238), paid)
- **iOS**: Tampermonkey for Safari ([App Store](https://apps.apple.com/us/app/tampermonkey/id1482490089?mt=12), $1.99)
- _**iOS**: Userscripts for Safari ([App Store](https://apps.apple.com/us/app/userscripts/id1463298887))_ — Users report not working.

Once that's done, you can [click here to install the latest RxE script](https://raw.githubusercontent.com/Ritsu-Projects/Public-Releases/main/ritsu-emerald.user.js). 
Alternatively, select a script in the repository to load a specific version (and then click on the <kbd>Raw</kbd> button). If your userscript manager doesn't prompt you to install the script, download it from the link and add it manually (for Tampermonkey, that's Utilities -> File -> Import).
**Warning: Never install scripts from untrusted sources.**

_(Have a free working setup for iOS? [Open an issue](https://github.com/Ritsu-Projects/Public-Releases/issues/new/choose) and you might see it here.)_

## Features

*(This list is incomplete.)*

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
  - Blurred images
  - Favourite images
  - Image blocking
- **Fixes**
  - Broken DMs
  - Crashed GC
  - Chat stays muted
  - Chat history


- **Coming soon** (v11.0):
  - Profile pictures¹
  - Image sending²
  - Permanent muting
  - Blocking friend requests
  - Highlighted name mentions
  - Clickable links
  - [Material Icons](https://fonts.google.com/icons?selected=Material+Icons)¹ (using `m:icon_name:`)

¹ - between RxE users.

² - non-RxE users see link; uploading new images has a cooldown.

### Screenshots

_(Want your screenshot featured here? [Open an issue](https://github.com/Ritsu-Projects/Public-Releases/issues/new) or get in touch with the team members.)_

## Privacy

RxE stores settings in your browser. RxE also sends data on your behalf to EmeraldChat when including your profile picture in your bio (v11.0+). RxE sends your picture to [Imgur](https://imgurinc.com/privacy) when uploading an image for use in chat or an Imgur profile picture (v11.0+).
