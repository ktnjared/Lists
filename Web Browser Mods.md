# Web Browser Mods

## Extensions

### Firefox

#### AMO (addons.mozilla.org)

Extensions that are used in my Profiles. This list is also maintained as a [Collection on AMO].

| Extension                          | AMO Page                                                             |
| ---------------------------------- | -------------------------------------------------------------------- |
| [1Password]                        | [1password-x-password-manager][AMO 1password-x-password-manager]     |
| [Auto Mute Plus]                   | [auto-mute-plus][AMO auto-mute-plus]                                 |
| Color Inverter                     | [color-inverter-css][AMO color-inverter-css]                         |
| [Containerise]                     | [containerise][AMO containerise]                                     |
| [Containers Helper]                | [containers-helper][AMO containers-helper]                           |
| [cookies.txt]                      | [cookies-txt][AMO cookies-txt]                                       |
| [DeArrow]                          | [dearrow][AMO dearrow]                                               |
| [Enhancer for YouTube]             | [enhancer-for-youtube][AMO enhancer-for-youtube]                     |
| [Image Max URL]                    | [image-max-url][AMO image-max-url]                                   |
| [Image Search Options]             | [image-search-options][AMO image-search-options]                     |
| JPEG XL Viewer                     | [jxl][AMO jxl]                                                       |
| [LocalCDN]                         | [localcdn-fork-of-decentraleyes][AMO localcdn-fork-of-decentraleyes] |
| [Merge Windows]                    | [merge-window][AMO merge-window]                                     |
| [Old Reddit Redirect]              | [old-reddit-redirect][AMO old-reddit-redirect]                       |
| [Progressive Web Apps for Firefox] | [pwas-for-firefox][AMO pwas-for-firefox]                             |
| [Reddit Enhancement Suite]         | [reddit-enhancement-suite][AMO reddit-enhancement-suite]             |
| [Refined GitHub]                   | [refined-github-][AMO refined-github-]                               |
| [Save webP as PNG or JPEG]         | [save-webp-as-png-or-jpeg][AMO save-webp-as-png-or-jpeg]             |
| [Something Awful Last Read Redux]  | [salr-redux][AMO salr-redux]                                         |
| [Sort Tabs]                        | [sort-tabs-00][AMO sort-tabs-00]                                     |
| [StreetPass for Mastodon]          | [streetpass-for-mastodon][AMO streetpass-for-mastodon]               |
| [Switch Container]                 | [switch-container][AMO switch-container]                             |
| Tab Auto Refresh                   | [tab-auto-refresh][AMO tab-auto-refresh]                             |
| [Tampermonkey]                     | [tampermonkey][AMO tampermonkey]                                     |
| [Tweaks for VSCO]                  | [tweaks-for-vsco][AMO tweaks-for-vsco]                               |
| [uBlacklist]                       | [ublacklist][AMO ublacklist]                                         |
| [Velja]                            | [velja][AMO velja]                                                   |
| View Image Context Menu Item       | [view-image-context-menu-item][AMO view-image-context-menu-item]     |

#### Other Sources

| Extension                         | Install                                                                                                                                                                                                  |
| --------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [StopTheMadness Pro] <sup>1</sup> | Open<br>`file:///Applications/StopTheMadness Pro.app/Contents/MacOS/StopTheMadness Firefox.app/Contents/Resources/install.html`<br>in Firefox, Firefox Developer Edition, or Firefox Nightly to install. |
| [uBlock Origin]                   | [github.com/gorhill/uBlock][uBlock Origin GitHub]                                                                                                                                                        |

<sup>1</sup>: StopTheMadness Pro is only available on Apple platforms (macOS, iOS, iPadOS, visionOS).

### Safari

Some notes:

- This setup is also used with [Safari Technology Preview].
- Profiles vs PWAs:
    - Extensions for PWAs are only available on macOS. iOS and iPadOS lack this feature (for now?).
    - If/Once Extensions for PWAs are added to iOS and iPadOS, then Profiles will move to being PWAs.

The following tables details which extensions are enabled for which Safari Profiles.

#### App Store

| Extension              | App Store    | Main | Bluesky | GitHub | Mastodon | Twitch | YouTube |
| ---------------------- | ------------ | ---- | ------- | ------ | -------- | ------ | ------- |
| [1Password]            | [1569813296] | x    | x       | x      | x        | x      | x       |
| [DeArrow for YouTube]  | [6451469297] |      |         |        |          |        | x       |
| [Keyword Search]       | [1558453954] | x    | x       | x      | x        | x      | x       |
| [Refined GitHub]       | [1519867270] |      |         | x      |          |        |         |
| [StopTheMadness Pro]   | [6471380298] | x    | x       | x      | x        | x      | x       |
| [Tampermonkey]         | [6738342400] | x    | x       | x      | x        | x      | x       |
| [Velja] <sup>2</sup>   | [1607635845] | x    | x       | x      | x        | x      | x       |
| [Wipr 2] "Blocklist 1" | [1662217862] | x    | x       | x      | x        | x      | x       |
| [Wipr 2] "Blocklist 2" | [1662217862] | x    | x       | x      | x        | x      | x       |
| [Wipr 2] "Blocklist 3" | [1662217862] | x    | x       | x      | x        | x      | x       |
| [Wipr 2] "Blocklist 4" | [1662217862] | x    | x       | x      | x        | x      | x       |
| [Wipr 2] "Wipr Extra"  | [1662217862] | x    | x       | x      | x        | x      | x       |

<sup>2</sup>: "Velja" is included with [Velja] and cannot be removed.

#### Non-App Store

| Extension                      | Main | Bluesky | GitHub | Mastodon | Twitch | YouTube |
| ------------------------------ | ---- | ------- | ------ | -------- | ------ | ------- |
| [Auto Reload]                  |      |         |        |          | x      |         |
| Open in IINA <sup>3</sup>      |      |         |        |          |        |         |
| Subscribe to Feed <sup>4</sup> |      |         |        |          |        |         |

<sup>3</sup>: "Open in IINA" is included with [IINA] and cannot be removed.<br>
<sup>4</sup>: "Subscribe to Feed" is included [NetNewsWire] and cannot be removed.

## Userscripts

### Personal

Userscripts I've written for my own needs. Mainly for a more portable CSS override on browsers when [uBlock Origin] or [StopTheMadness Pro] is not available. Scripts are available at [https://github.com/ktnjared/userscripts].

| Top-Level Domain | Userscript Name                                                   |
| ---------------- | ----------------------------------------------------------------- |
| *                | (ktn) <all_urls>                                                  |
| backloggd.com    | (ktn) backloggd.com                                               |
| bitbang.social   | (ktn) bitbang.social                                              |
| bsky.app         | (ktn) Bluesky Quick Block (fork of [Bluesky Tanza3D Quick Block]) |
| bsky.app         | (ktn) bsky.app WIP                                                |
| cultdeadcow.com  | (ktn) cultdeadcow.com                                             |
| icy-veins.com    | (ktn) icy-veins.com                                               |
| Pi-hole          | (ktn) Pi-hole                                                     |
| pixiv.net        | (ktn) pixiv.net                                                   |
| reddit.com       | (ktn) reddit.com                                                  |
| youtube.com      | (ktn) youtube.com                                                 |

### Third-Party

Userscripts found out there, sourced from the likes of
[`"// Userscript"` on GitHub],
[`r/userscripts` on Reddit],
[Greasyfork],
[OpenUserJS],
et al.

| Top-Level Domain | Userscript Name                                    |
| ---------------- | -------------------------------------------------- |
| *                | Double-click Image Downloader                      |
| *~700 domains*   | Bypass All Shortlinks Debloated                    |
| *~355 domains*   | tinyShield                                         |
| *~100 domains*   | Bypass Paywalls Clean - en                         |
| *~5 domains*     | Stop videos looping                                |
| *~3 domains*     | CRX Downloader                                     |
| bitbang.social   | TangerineUI for Mastodon                           |
| bsky.app         | Block button in dropdown                           |
| google.com       | View Image                                         |
| instagram.com    | IG Helper                                          |
| spotify.com      | spotdl-interact-web                                |
| spotify.com      | Spotify Enhancer (Full-Sized Cover Art Downloader) |
| spotify.com      | Spotify Enhancer (Spotify to YouTube)              |
| telegram.org     | Telegram Media Downloader                          |
| twitch.tv        | FrankerFaceZ                                       |
| xbox.com         | Better xCloud                                      |
| youtube.com      | Simple youTube Age Restriction Bypass              |
| youtube.com      | YouTube: CPU Tamer                                 |

<!-- URLs -->
[`"// Userscript"` on GitHub]: https://github.com/search?q=%22%2F%2F%20%3D%3DUserScript%3D%3D%22&type=repositories
[`r/userscripts` on Reddit]: https://reddit.com/r/userscripts/
[1519867270]: https://apps.apple.com/us/app/refined-github/id1519867270
[1558453954]: https://apps.apple.com/us/app/keyword-search/id1558453954
[1569813296]: https://apps.apple.com/us/app/1password-for-safari/id1569813296
[1607635845]: https://apps.apple.com/us/app/velja/id1607635845
[1662217862]: https://apps.apple.com/us/app/wipr-2/id1662217862
[1Password]: https://1password.com/downloads/browser-extension
[6451469297]: https://apps.apple.com/us/app/dearrow-for-youtube/id6451469297
[6471380298]: https://apps.apple.com/us/app/stopthemadness-pro/id6471380298
[6738342400]: https://apps.apple.com/us/app/tampermonkey/id6738342400
[AMO 1password-x-password-manager]: https://addons.mozilla.org/firefox/addon/1password-x-password-manager/
[AMO auto-mute-plus]: https://addons.mozilla.org/firefox/addon/auto-mute-plus/
[AMO color-inverter-css]: https://addons.mozilla.org/firefox/addon/color-inverter-css/
[AMO containerise]: https://addons.mozilla.org/firefox/addon/containerise/
[AMO containers-helper]: https://addons.mozilla.org/firefox/addon/containers-helper/
[AMO cookies-txt]: https://addons.mozilla.org/firefox/addon/cookies-txt/
[AMO dearrow]: https://addons.mozilla.org/firefox/addon/dearrow/
[AMO enhancer-for-youtube]: https://addons.mozilla.org/firefox/addon/enhancer-for-youtube/
[AMO image-max-url]: https://addons.mozilla.org/firefox/addon/image-max-url/
[AMO image-search-options]: https://addons.mozilla.org/firefox/addon/image-search-options/
[AMO jxl]: https://addons.mozilla.org/firefox/addon/jxl/
[AMO localcdn-fork-of-decentraleyes]: https://addons.mozilla.org/firefox/addon/localcdn-fork-of-decentraleyes/
[AMO merge-window]: https://addons.mozilla.org/firefox/addon/merge-window/
[AMO old-reddit-redirect]: https://addons.mozilla.org/firefox/addon/old-reddit-redirect/
[AMO pwas-for-firefox]: https://addons.mozilla.org/firefox/addon/pwas-for-firefox/
[AMO reddit-enhancement-suite]: https://addons.mozilla.org/firefox/addon/reddit-enhancement-suite/
[AMO refined-github-]: https://addons.mozilla.org/firefox/addon/refined-github-/
[AMO salr-redux]: https://addons.mozilla.org/firefox/addon/salr-redux/
[AMO save-webp-as-png-or-jpeg]: https://addons.mozilla.org/firefox/addon/save-webp-as-png-or-jpeg/
[AMO sort-tabs-00]: https://addons.mozilla.org/firefox/addon/sort-tabs-00/
[AMO streetpass-for-mastodon]: https://addons.mozilla.org/firefox/addon/streetpass-for-mastodon/
[AMO switch-container]: https://addons.mozilla.org/firefox/addon/switch-container/
[AMO tab-auto-refresh]: https://addons.mozilla.org/firefox/addon/tab-auto-refresh/
[AMO tampermonkey]: https://addons.mozilla.org/firefox/addon/tampermonkey/
[AMO tweaks-for-vsco]: https://addons.mozilla.org/firefox/addon/tweaks-for-vsco/
[AMO ublacklist]: https://addons.mozilla.org/firefox/addon/ublacklist/
[AMO velja]: https://addons.mozilla.org/firefox/addon/velja/
[AMO view-image-context-menu-item]: https://addons.mozilla.org/firefox/addon/view-image-context-menu-item/
[Auto Mute Plus]:https://github.com/rogerskeie/autoMutePlus
[Auto Reload]: https://github.com/garrettrayj/auto-reload
[Bluesky Tanza3D Quick Block]: https://github.com/Tanza3D/bluesky-quick-block
[Collection on AMO]: https://addons.mozilla.org/firefox/collections/13879288/Daily-Driver/?page=1&collection_sort=name
[Containerise]: https://github.com/kintesh/containerise
[Containers Helper]: https://codeberg.org/charles-m-knox/firefox-containers-helper
[cookies.txt]: https://github.com/hrdl-github/cookies-txt
[DeArrow for YouTube]: https://dearrow.ajay.app/
[DeArrow]: https://dearrow.ajay.app/
[Enhancer for YouTube]: https://www.mrfdev.com/enhancer-for-youtube
[Greasyfork]: https://greasyfork.org/
[IINA]: https://iina.io/
[Image Max URL]: https://github.com/qsniyg/maxurl
[Image Search Options]: https://saucenao.com/tools/
[Keyword Search]: http://safarikeywordsearch.aurlien.net/
[LocalCDN]: https://codeberg.org/nobody/LocalCDN
[Merge Windows]: https://github.com/jonathanKingston/merge-windows
[NetNewsWire]: https://netnewswire.com/
[Old Reddit Redirect]: https://github.com/tom-james-watson/old-reddit-redirect
[OpenUserJS]: https://openuserjs.org
[Progressive Web Apps for Firefox]: https://pwasforfirefox.filips.si/
[Reddit Enhancement Suite]: https://github.com/honestbleeps/Reddit-Enhancement-Suite
[Refined GitHub]: https://github.com/refined-github/refined-github
[Safari Technology Preview]: https://developer.apple.com/safari/technology-preview/
[Save webP as PNG or JPEG]: https://github.com/jscher2000/Save-webP-as-extension
[Something Awful Last Read Redux]: https://github.com/astral-sa/salr-redux
[Sort Tabs]: https://github.com/yshui/sorttabs
[StopTheMadness Pro]: https://underpassapp.com/StopTheMadness/Pro/New.html
[StreetPass for Mastodon]: https://github.com/tvler/streetpass
[Switch Container]: https://gitlab.com/mjanetmars/switch-container
[Tampermonkey]: https://www.tampermonkey.net/index.php
[Tweaks for VSCO]: https://inzk.dev/
[uBlacklist]: https://github.com/iorate/ublacklist
[uBlock Origin GitHub]: https://github.com/gorhill/uBlock
[uBlock Origin]: [https://ublockorigin.com/]
[Velja]: https://sindresorhus.com/velja
[Wipr 2]: https://kaylees.site/wipr2.html
