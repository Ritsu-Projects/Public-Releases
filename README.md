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
- Install RxE into your browser by [clicking here](https://github.com/Ritsu-Projects/Public-Releases/raw/main/Ritsu%20x%20Emerald.0.11.0.user.js).
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

- <ins>Cosmetic</ins>: Themes, **<ins>custom name colour</ins>**, customizable layout, 
- <ins>Images</ins>: **<ins>Profile pictures</ins>**, image sending, own avatar gallery
- <ins>Chat</ins>: \*\***Bold**\*\* & \**italics*\*, **<ins>clickable links</ins>**, highlighted name mentions, chat commands (`.shrug`, `.rxelink`, etc.), support for [material icons](https://fonts.google.com/icons?selected=Material+Icons) (using `m:icon_name:`)
- <ins>Annoyances</ins>: **<ins>Permanent muting</ins>**, **<ins>spam blocker</ins>**, ad blocker, **<ins>blocking friend requests</ins>**, image blurring
- <ins>Unbreaking</ins>: Fixed layout, **<ins>fixed DMs</ins>**, fixed group chat, working DM history, muting chat sounds works
- <ins>Utilities</ins>: Image favoriting, **<ins>extra user info</ins>**, tracking karma live

### Screenshots

The following are some screenshots of RxE:
#### Main menu with RxE (Different themes)
<img src="https://user-images.githubusercontent.com/86239876/168598300-315f8c22-bf96-4a7c-8ae4-aef1190899f2.png" width = 450> <img src="https://user-images.githubusercontent.com/86239876/168598294-3c0eae3a-1f3a-4a58-b6a0-9902ed9b14aa.png" width = 450>

#### Edit Profile with RxE
<img src="https://user-images.githubusercontent.com/86239876/168598213-ffd778f0-6cd9-4d9e-865d-6a5bf2efe01f.png" width = 450>

#### Your profile with RxE
<img src="https://user-images.githubusercontent.com/86239876/168598125-eeaf25a3-4245-4322-a3db-15569aa05bf1.png" width = 450>

#### Groupchat with RxE
<img src="https://i.ibb.co/JkyMVfq/rxe-1.png" width = 450>

#### User options with RxE

<img src="https://user-images.githubusercontent.com/86239876/168603777-198c5495-7976-4324-b0e6-03ce3a9d15a8.png" width = 450>

#### RxE's custom settings
<img src="https://user-images.githubusercontent.com/86239876/168600558-c724664f-6b6f-4305-9296-e46634eec22c.png" width = 450>

_(Want your screenshot featured here? [Open an issue](https://github.com/Ritsu-Projects/Public-Releases/issues/new) or get in touch with the team members.)_

## Privacy

Ritsu x Emerald doesn't collect or publish any data about you — it's just a simple addon.

For privacy-minded people:
- RxE stores settings in your browser.
- When including your profile picture in your bio, RxE sends data on your behalf to EmeraldChat to do so.
- When uploading an image for use in chat or an Imgur profile picture, RxE sends your picture to Imgur ([Privacy Policy](https://imgurinc.com/privacy)).
