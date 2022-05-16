# Ritsu x Emerald

A small addon to make EmeraldChat less bad.

Contents:

1. [How do I install RxE?](#installation)
    1. [Mobile Browsers](#mobile-browsers)
    1. [Installing RxE](#installing-rxe)
    1. [What if I can't get RxE?](#what-if-i-cant-get-rxe)
1. [What does it do?](#features)
    1. [Upcoming features](#upcoming-features)
    1. [Screenshots](#screenshots)
3. [Do you collect my data?](#privacy)

## Installation

**To install RxE, follow these steps**:
- (*Android / Apple*) Get a suitable browser (see [Mobile Browsers](#mobile-browsers)).
- Install a **userscript manager** as a browser extension ([ViolentMonkey](https://violentmonkey.github.io/) or [TamperMonkey](https://www.tampermonkey.net/)).
- Install RxE into your browser by [clicking here](https://raw.githubusercontent.com/Ritsu-Projects/Public-Releases/main/ritsu-emerald.user.js).
- Refresh EmeraldChat, and change your settings in the new **Ritsu Menu**.

### Mobile Browsers

To use RxE on mobile, choose one of the following options: 
- **Android**: Kiwi Browser
([Google Play Store](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser)) - 
Chromium-based browser with Chrome extension support and extra features.
- **Android**: Firefox Nightly 
([Google Play Store](https://play.google.com/store/apps/details?id=org.mozilla.fenix), 
[YouTube Tutorial](https://youtu.be/GXcg8r0c-Lk?t=232), 
[Blog Post](https://blog.mozilla.org/addons/2020/09/29/expanded-extension-support-in-firefox-for-android-nightly/)) - 
 newest available version of Firefox for Android. 
    <details><summary><strong>Tutorial</strong> (click to reveal)</summary>
    On PC, create an add-on collection on <a href="https://addons.mozilla.org">addons.mozilla.org</a>, and add your userscript manager to the collection. 
    On Android, unlock Firefox Nightly's developer options by tapping the Firefox logo in the About Menu,
    and then input your User ID & collection from the collection URL as the "custom addon collection".</details>
- **iOS**: Alook Browser ([App Store](https://apps.apple.com/us/app/alook-browser-2x-speed/id1261944766), one-time fee)
- **iOS**: Gear Browser ([App Store](https://apps.apple.com/us/app/gear-browser/id1458962238), subscription-based)
- **iOS**: Tampermonkey for Safari ([App Store](https://apps.apple.com/us/app/tampermonkey/id1482490089?mt=12), $1.99)
- **iOS**: Tampermonkey for Safari — versions 6 to 11 ([Extension File](https://www.tampermonkey.net/?ext=dhdg&browser=safari))

_(Have a free working setup for iOS? [Open an issue](https://github.com/Ritsu-Projects/Public-Releases/issues/new/choose) and you might see it here. See [Stack Exchange discussion](https://apple.stackexchange.com/questions/31562/is-there-something-similar-to-the-greasemonkey-script-system-for-a-browser-in-io) for more details on iOS support.)_

### Installing RxE

Once that's done, you can [click here to install the latest RxE script](https://raw.githubusercontent.com/Ritsu-Projects/Public-Releases/main/ritsu-emerald.user.js). 
Alternatively, select a script in the repository to load a specific version (and then click on the <kbd>Raw</kbd> button). If your userscript manager doesn't prompt you to install the script, download it from the link and add it manually (for Tampermonkey, that's Utilities -> File -> Import).
**Warning: Never install scripts from untrusted sources.**

### What if I can't get RxE?

If you are on an unsupported device, or the installation process is too complicated for you, check if you can still fix crashed DMs with **uBlock Origin**:
- Add the [uBlock Origin](https://ublockorigin.com/) extension to your browser.
- Open its settings, and navigate to the **My Filters** tab.
- Paste the following: `https://emeraldchat.com/private_friends`
- Click **Apply changes**.

This will allow you to open DMs, but the DMs panel will no longer be available.

## Features

- <ins>Cosmetic</ins>: Themes, customizable layout, **<ins>custom name colour</ins>**, extra user info
- <ins>Annoyances</ins>: **<ins>Spam blocker</ins>**, ad blocker
- <ins>Unbreaking</ins>: Fixed layout, **<ins>broken GC or DMs</ins>**, muting chat sounds works
- <ins>Karma</ins>: Tracking karma live

### Upcoming features
- **<ins>Profile pictures</ins>** (RxE-only)
- Image sending, blurring & favouriting
- **<ins>Permanent muting</ins>**
- Blocking friend requests
- **<ins>Chat commands</ins>** (`.shrug`, `.rxelink`, etc.)
- Own picture gallery
- \*\***Bold**\*\* and \**italics*\*
- Highlighted name mentions
- **<ins>Clickable links</ins>**
- Working DM history
- [Material Icons](https://fonts.google.com/icons?selected=Material+Icons)¹ (using `m:icon_name:`) (RxE-only)

### Screenshots

The following are some screenshots of the upcoming version of RxE:

#### Main menu with RxE
![Main menu](https://i.ibb.co/zPnBQSk/rxe-2.png)

#### Edit Profile with RxE
![Edit Profile](https://i.ibb.co/9cKK4W5/rxe-5.png)

#### Your profile with RxE
![Your profile](https://i.ibb.co/6XFQm0v/rxe-6.png)

#### Groupchat with RxE
![Group chat](https://i.ibb.co/JkyMVfq/rxe-1.png)

#### User options with RxE
![User options](https://i.ibb.co/8m7GLsc/rxe-7.png)

#### RxE's custom settings
![Custom settings](https://i.ibb.co/Qc1fnd4/rxe-3.png)

_(Want your screenshot featured here? [Open an issue](https://github.com/Ritsu-Projects/Public-Releases/issues/new) or get in touch with the team members.)_

## Privacy

Ritsu x Emerald doesn't collect or publish any data about you — it's just a simple addon.

For privacy-minded people:
- RxE stores settings in your browser.

The following apply from version **v0.11.0**:
- When including your profile picture in your bio, RxE sends data on your behalf to EmeraldChat to do so.
- When uploading an image for use in chat or an Imgur profile picture, RxE sends your picture to Imgur ([Privacy Policy](https://imgurinc.com/privacy)).
