<p align="center"><a href="https://arcomage.github.io/"><img width="250" src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/assets/logo/logo.svg" alt="ArcoMage HD logo"><br><br><strong>arcomage.github.io</strong></a></p>

<h1 align="center">ArcoMage HD - Open Source Card Game</h1>

**ArcoMage HD** is a web-based, open source, remastered 3D clone of 3DO and New World Computing's 2000 PC card game Arcomage, which appeared in the *Might and Magic* RPG game series.

This not-for-profit fan-remake of the tower defense, resource management fantasy game is developed by [@tomchen](https://github.com/tomchen) with TypeScript + React + Redux + redux-observable + RxJS + CSS-based animations + WebRTC (see [§ Development](#development)). Please star the repo / follow me to support me.

It's available in 10 languages: English, French, German, Simplified Chinese, Traditional Chinese, Spanish, Italian, Russian, Czech, Polish.

The default single player mode (against computer AI 🤖) is stable✔️. I recently added [Multiplayer Mode 🧑‍🤝‍🧑](#multiplayer-mode) which is generally good but may need more tests🧪. Click gear ⚙️ icon in the game to open the "Preferences" window so you can change settings and/or switch to Multiplayer Mode.

It supports <a href="https://www.google.com/chrome/" title="Google Chrome"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/browsers/chrome.svg" alt="Google Chrome" width="21px" height="21px"></a> <a href="https://www.mozilla.org/firefox/browsers/" title="Firefox"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/browsers/firefox.svg" alt="Firefox" width="21px" height="21px"></a> <a href="https://www.apple.com/safari/" title="Safari"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/browsers/safari.svg" alt="Safari" width="21px" height="21px"></a> <a href="https://www.microsoft.com/edge" title="Microsoft Edge"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/browsers/edge.svg" alt="Microsoft Edge" width="21px" height="21px"></a> <a href="https://www.opera.com/" title="Opera"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/browsers/opera.svg" alt="Opera" width="21px" height="21px"></a> <a href="https://www.samsung.com/us/support/owners/app/samsung-internet" title="Samsung Internet"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/browsers/samsung_internet.svg" alt="Samsung Internet" width="21px" height="21px"></a> and other modern browsers (it works best in Chrome and browsers with Chrome's Blink engine, and may or may not have performance issues in Safari & Firefox. Safari, Firefox, IE users can use [the Desktop Version](#desktop-version) instead).

It supports desktop / tablet / mobile screen 🖥️💻📱. [It's a PWA, meaning you can install it and play it offline](#play-it-offline-pwa).

<p align="center"><a href="https://arcomage.github.io/"><strong>Click to play it now</strong><br><br><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/assets/misc/ogimage.jpg" alt="ArcoMage HD screenshot"></a></p>

<p align="center">
<a href="https://github.com/arcomage/arcomage-hd/"><img src="https://img.shields.io/github/package-json/v/arcomage/arcomage-hd" alt="version number"></a>
<a href="https://github.com/arcomage/arcomage-hd/actions/workflows/test.yml"><img src="https://github.com/arcomage/arcomage-hd//workflows/Test/badge.svg" alt="Actions Status"></a>
<a href="https://github.com/arcomage/arcomage-hd/blob/main/LICENSE.md"><img src="https://img.shields.io/badge/license-MIT-brightgreen" alt="License"></a>
</p>

## Gameplay

<p align="center"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/manual.jpg" alt="ArcoMage HD Manual Image"></a></p>

<details><summary><strong>Click to show game rules in text form</strong></summary>

> Victory conditions vary per tavern. Build your tower, destroy your opponent's tower, or collect enough resources before your opponent does.
> 
> Large yellow numbers in column are the productions. This is how many new units of a particular resource you will receive on your next turn. Small black numbers in column are the resources. This is how many units you have available to spend on your current turn.
> 
> Cards: Each have their own cost to play, indicated in a small circle in the lower right corner of the card. The cost will be deducted from your resources according to the color of the card. Left click on a card plays the card. Right click on a card to discard without playing.
> 
> Red represents your Quarry Generator which produces your Brick 🧱 resources, blue represents your Magic Generator which produces Gem 💎 resources, green represents your Dungeon (aka. Zoo) generator which produces Recruit (aka. Beast) 🐲 resources.

</details>

## Play It Offline (PWA)

The image and sound files, as well as the card and language settings, are automatically stored in your browser. In addition, you can install this "Progressive Web App" (PWA) on your computer or smartphone. [Google Chrome's article on how to install PWA](https://support.google.com/chrome/answer/9658361).

Depending on your browser, sometimes you may need to press <kbd>Ctrl</kbd> + <kbd>F5</kbd> to clear the cache files & reload arcomage.github.io webpage to have the latest version of the game.

## Desktop Version

**If you don't have performance issues playing ArcoMage HD in your browser, then you don't need to use the Desktop Version.**

Some browsers, such as Firefox and Safari, that are not Chrome's engine based, may (or may not) be a bit slow running ArcoMage HD. In this case, you can use the Desktop Version.

The Desktop Version is **merely a Google Chrome browser-like wrapper** that visits the URL [https://arcomage.github.io/](https://arcomage.github.io/).

[Click to download the Desktop Version (Windows)](https://github.com/arcomage/arcomage-hd/releases/download/v1.0.0-beta.26/ArcoMage.HD.Setup.1.0.0.7z)

<details><summary><strong>Click to show more details on the Desktop Version</strong></summary>

### Do I Need Desktop Version? (browser list)

If you are using "fully supported" browser, then it's likely you don't need the Desktop Version.

Browsers based on Chrome's engine (Blink or WebKit) are fully supported by ArcoMage HD (as of 2021):

*(\*: I didn't really test these browsers)*

* Google Chromium
* Google Chrome
* Brave
* Edge
* Opera \*
* Maxthon \*
* Vivaldi \*
* QQ \*
* Sogou \*
* Baidu \*
* WeChat's browser
* Yandex Browser \*
* UC Browser \*
* CM Browser \*
* etc.

Browsers not or partially based on Chrome's engine, and may or may not run ArcoMage HD very well, therefore you can use the Desktop Version:

* Internet Explorer: this old browser, of course, does not work
* Firefox & Safari: you can play the game with these browsers, but they do not have as good performance as Chrome's engine based browsers therefore may be a bit slow, it depends on your CPU / GPU
  * Pale Moon \*

### Other Remarks

The Desktop Version is not expected to be updated. The Desktop Version's version number is different from ArcoMage HD's. Actually the Desktop Version may stays v1.0.0 forever unless there's really something to update.

The first time you run ArcoMage HD Desktop Version, it downloads all the images and sound files silently. You should wait maybe 1 minute (depending on your Internet speed), before you can cut off Internet and play it completely offline.

If you install both Google Chrome and the Desktop Version, the Desktop Version will have independent storage. Clearing your Google Chrome's stored data will not reset the Desktop Version's settings.

</details>

## Keyboard Control

The game is fully controllable with keyboard. Use <kbd>Tab</kbd> (or <kbd>Option (Alt)</kbd> + <kbd>Tab</kbd> in Safari) to select a top-menu icon or a card, then <kbd>Enter</kbd> to open or use it, <kbd>Delete</kbd> / <kbd>Backspace</kbd> to discard a card, <kbd>Esc</kbd> to close a preferences window.

<details><summary><strong>Click to show the detailed keyboard control instruction & additional special "Access Key" usage (e.g. <kbd>Alt</kbd> + <kbd>P</kbd>: Preferences; <kbd>Alt</kbd> + <kbd>1</kbd>: use the 1st card ...)</strong></summary>

### Top Menu

Use <kbd>Tab</kbd> to select an icon (it's <kbd>Option (Alt)</kbd> + <kbd>Tab</kbd> in Safari), then <kbd>Enter</kbd> to open it. When the window is open, use <kbd>Esc</kbd> to close it.

Or with access key (only for opening a window):

* <kbd>Alt</kbd> + <kbd>P</kbd>: Preferences
* <kbd>Alt</kbd> + <kbd>L</kbd>: Language
* <kbd>Alt</kbd> + <kbd>V</kbd>: Volume
* <kbd>Alt</kbd> + <kbd>T</kbd>: Toggle Fullscreen
* <kbd>Alt</kbd> + <kbd>H</kbd>: Help
* <kbd>Alt</kbd> + <kbd>G</kbd>: GitHub

### Card

Use <kbd>Tab</kbd> to select a card (it's <kbd>Option (Alt)</kbd> + <kbd>Tab</kbd> in Safari), then <kbd>Enter</kbd> to **use** it, or <kbd>Delete</kbd> / <kbd>Backspace</kbd> to **discard** it.

Or with access key (only for using a card):

* <kbd>Alt</kbd> + <kbd>1</kbd>: Use the 1st card
* <kbd>Alt</kbd> + <kbd>2</kbd>: Use the 2nd card
* <kbd>Alt</kbd> + <kbd>3</kbd>: Use the 3rd card
* <kbd>Alt</kbd> + ...: Use the nth card (n <= 9, you can't use 10th or later card with access key)

It could be other key instead of <kbd>Alt</kbd>

[The way to activate the accesskey depends on the browser and its platform](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/accesskey), it's "<kbd>Alt</kbd> + key" in Chrome Windows/Linux.

</details>

## Multiplayer Mode

*(Multiplayer Mode is experimental🧪 and may be unstable)*

### How To Use the Multiplayer Mode

https://user-images.githubusercontent.com/529949/115864733-941cbd00-a437-11eb-955d-f6a341c8ea64.mp4

Both players enable the "Multiplayer" Mode. Bob 🧝 must copy and **give his ID to Alice 👧 via Discord or other platforms or forums**. Alice 👧 then enters Bob 🧝's ID and connect to Bob 🧝. Alice 👧 becomes the host 🏠 (i.e. technically it's her computer that deals cards) and Bob 🧝 is the guest 💼.

<details><summary><strong>Click to show technical details</strong></summary>

### Technical

In Multiplayer Mode, you are connected directly to your opponent (Peer to Peer, P2P) without server. However, we still need a free public relay server. Once we use the ID assigned by the relay server to connect to each other, we are connected directly and don't need the server any more.

The game operates no servers at all, therefore it does not have a server that stores a "list of players online" so you can choose your opponent more easily. You have to instead give your ID to your opponent via Discord or other platforms.

The relay servers used here are free STUN servers set up by Google and others.

[WebRTC (Web Real-Time Communication)](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API) is used for the Peer to Peer communication.

</details>

## Development

The stack:

<p align="center">
<a href="https://www.typescriptlang.org/" title="Typescript"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/typescript-icon.svg" alt="Typescript" width="21px" height="21px"></a>
<a href="https://reactjs.org/" title="React"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/react.svg" alt="React" width="21px" height="21px"></a>
<a href="https://redux.js.org/" title="Redux"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/redux.svg" alt="Redux" width="21px" height="21px"></a>
<a href="https://github.com/redux-observable/redux-observable" title="redux-observable"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/redux-observable.svg" alt="redux-observable" width="21px" height="21px"></a>
<a href="https://rxjs-dev.firebaseapp.com/" title="RxJS (ReactiveX)"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/reactivex.svg" alt="RxJS (ReactiveX)" width="21px" height="21px"></a>
<a href="https://webrtc.org/" title="WebRTC"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/webrtc.svg" alt="WebRTC" width="21px" height="21px"></a>
<a href="https://developers.google.com/web/tools/workbox" title="Workbox"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/workbox-icon.svg" alt="Workbox" width="21px" height="21px"></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" title="JavaScript"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/javascript.svg" alt="JavaScript" width="21px" height="21px"></a>
<a href="https://tc39.es/ecma262/" title="ECMAScript 6+"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/es6.svg" alt="ECMAScript 6+" width="21px" height="21px"></a>
<a href="https://sass-lang.com/" title="Sass"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/sass.svg" alt="Sass" width="21px" height="21px"></a>
<a href="https://tailwindcss.com/" title="Tailwind CSS"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/tailwindcss-icon.svg" alt="Tailwind CSS" width="21px" height="21px"></a>
<a href="https://material-ui.com/" title="Material-UI"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/material-ui.svg" alt="Material-UI" width="21px" height="21px"></a>
<a href="https://webpack.js.org/" title="webpack"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/webpack.svg" alt="webpack" width="21px" height="21px"></a>
<a href="https://jestjs.io/" title="Jest"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/jest.svg" alt="Jest" width="21px" height="21px"></a>
<a href="https://cssinjs.org/" title="JSS"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/jss.svg" alt="JSS" width="21px" height="21px"></a>
<a href="https://prettier.io/" title="Prettier"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/prettier.svg" alt="Prettier" width="21px" height="21px"></a>
<a href="https://eslint.org/" title="ESLint"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/eslint.svg" alt="ESLint" width="21px" height="21px"></a>
<a href="https://github.com/postcss/postcss" title="PostCSS"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/postcss.svg" alt="PostCSS" width="21px" height="21px"></a>
<a href="https://github.com/postcss/autoprefixer" title="Autoprefixer"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/autoprefixer.svg" alt="Autoprefixer" width="21px" height="21px"></a>
<a href="https://code.visualstudio.com/" title="Visual Studio Code"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/visual-studio-code.svg" alt="Visual Studio Code" width="21px" height="21px"></a>
<a href="https://yarnpkg.com/" title="yarn v1"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/yarn.svg" alt="yarn v1" width="21px" height="21px"></a>
<a href="https://inkscape.org/" title="Inkscape"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/inkscape.svg" alt="Inkscape" width="21px" height="21px"></a>
<a href="https://www.adobe.com/products/illustrator.html" title="Adobe Illustrator"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/adobe-illustrator.svg" alt="Adobe Illustrator" width="21px" height="21px"></a>
<a href="https://www.adobe.com/products/photoshop.html" title="Adobe Photoshop"><img src="https://raw.githubusercontent.com/arcomage/arcomage-hd/main/misc/readme_images/stack/adobe-photoshop.svg" alt="Adobe Photoshop" width="21px" height="21px"></a>
</p>

TypeScript + React + Redux + redux-observable + RxJS, CSS-based animations without \<canvas\>. PWA (using Workbox). P2P Multiplayer Mode without server (only uses STUN servers as relay) with WebRTC (using PeerJS).

## To Do

[To-do list](https://github.com/arcomage/arcomage-hd/projects/1)

## Translation Credits

<details><summary><strong>Click to show the translation credits</strong></summary>

* [Cards](https://github.com/arcomage/arcomage-hd/tree/main/src/i18n/cards) & many other strings: from *Might and Magic VIII & VI* original game. Extracted (or retranslated) by:
  * English (`en`): [Black Rabite on GameFAQs](https://gamefaqs.gamespot.com/pc/929601-arcomage/faqs/44131)
  * Russian (`ru`) (retranslated): [rayburn](https://github.com/TombOfVARN)
  * Simplified Chinese (`zh-Hans`): [xyz53235](https://blog.csdn.net/xyz53235/article/details/113663313)
  * Polish (`pl`) (retranslated?): [acidcave](https://www.arcomage.acidcave.net/czerwone_karty.html)
  * Czech (`cs`): Yym
  * All others: [Tom Chen](https://github.com/tomchen) with OCR tool [tesseract.js](https://tesseract.projectnaptha.com/) & [other scripts](https://github.com/arcomage/arcomage-hd/tree/main/tools)
* [Main](https://github.com/arcomage/arcomage-hd/tree/main/src/i18n/main):
  * Russian (`ru`): [rayburn](https://github.com/TombOfVARN)
  * Polish (`pl`) (partially): Plamcia
  * All others: [Tom Chen](https://github.com/tomchen) by himself and/or with the help of [Google Translate](https://translate.google.com/) & [DeepL](https://www.deepl.com/translator)

See also [Issue #9](https://github.com/arcomage/arcomage-hd/issues/9)

</details>

## Arcomage original game

Arcomage was initially developed by Stickman Games and later sold to The 3DO Company (3DO). The game appeared as a mini-game in *Might and Magic VII: For Blood and Honor* (MM7) and *Might and Magic VIII: Day of the Destroyer* (MM8), the seventh and eighth games in New World Computing (NWC)'s *Might and Magic* (MM) series. (It's like *Gwent* in *The Witcher*) NWC and its parent company, 3DO, also released a stand-alone version in 2000, which can be played in single player or multi player mode. The original stand-alone Arcomage has a resolution of 800 x 600 pixels and is usable in 16-bit color mode in Windows 10, but the graphics is unstable.

## Copyright

The code of the ArcoMage HD game: MIT License (c) 2021 [Tom Chen](https://github.com/tomchen).

The assets, text, appearance and other copyrightable elements of the game: (c) 2001 The 3DO Company.

See [LICENSE.md file](LICENSE.md) for a detailed presentation of the copyright status of the game's components.
