# Web Browser Mods

## Extensions

### Firefox

- 1Password
- Auto Mute Plus
- Briteinno Images Format Save as
- Color Inverter
- Containerise
- Containers Helper
- Enhancer for YouTube
- Firefox Multi-Account Containers
- [Image Max URL] ([Mozilla AMO][image-max-url])
- Image Search Options
- JPEG XL Viewer
- LocalCDN
- Merge Windows
- Old Reddit Redirect
- Progressive Web Apps for Firefox
- Reddit Enhancement Suite
- Refined GitHub
- Save webP as PNG or JPEG
- Something Awful Last Read Redux
- StopTheMadness Pro
- StreetPass for Mastodon
- Switch Container
- Tab Auto Refresh
- Tampermonkey
- Tweaks for VSCO
- uBlacklist
- uBlock Origin
- Velja
- View Image Context Menu Item

[Image Max URL]: https://github.com/qsniyg/maxurl
[image-max-url]: https://addons.mozilla.org/firefox/addon/image-max-url/

### Safari

Some notes:

- This configuration is duplicated in Safari Technology Preview as well.
- Extensions for PWAs are only available on macOS. PWAs on iOS and iPadOS lack this feature (for now?). If/Once Extensions for PWAs become a reality on iOS and iPadOS, then Profiles will move to being PWAs.

The following table details which extensions are enabled for which Safari Profiles.

| Extension             | Main | Bluesky | GitHub | Mastodon | Twitch | YouTube |
| --------------------- | ---- | ------- | ------ | -------- | ------ | ------- |
| 1Password             | x    | x       | x      | x        | x      | x       |
| Auto Reload           |      |         |        |          | x      |         |
| DeArrow for YouTube   |      |         |        |          |        | x       |
| Open in IINA[^1]      |      |         |        |          |        |         |
| Keyword Search        | x    | x       | x      | x        | x      | x       |
| Subscribe to Feed[^2] |      |         |        |          |        |         |
| Refined GitHub        |      |         | x      |          |        |         |
| StopTheMadness Pro    | x    | x       | x      | x        | x      | x       |
| Tampermonkey          | x    | x       | x      | x        | x      | x       |
| Velja[^3]             | x    | x       | x      | x        | x      | x       |
| Wipr 2 "Blocklist 1"  | x    | x       | x      | x        | x      | x       |
| Wipr 2 "Blocklist 2"  | x    | x       | x      | x        | x      | x       |
| Wipr 2 "Blocklist 3"  | x    | x       | x      | x        | x      | x       |
| Wipr 2 "Blocklist 4"  | x    | x       | x      | x        | x      | x       |
| Wipr 2 "Wipr Extra"   | x    | x       | x      | x        | x      | x       |

[^1]: "Open in IINA" is included with [IINA] and cannot be removed.
[^2]: "Subscribe to Feed" is included [NetNewsWire] and cannot be removed.
[^3]: "Velja" is included with [Velja] and cannot be removed.

[IINA]: https://iina.io/
[NetNewsWire]: https://netnewswire.com/
[Velja]: https://sindresorhus.com/velja

## Userscripts

### Personal

Userscripts I've written for my own needs.

| Top-Level Domain | Userscript Name                                                     |
| ---------------- | ------------------------------------------------------------------- |
| *                | \[ktn\] <all_urls>                                                  |
| backloggd.com    | \[ktn\] backloggd.com                                               |
| bitbang.social   | \[ktn\] bitbang.social                                              |
| bsky.app         | \[ktn\] Bluesky Quick Block (fork of [Bluesky Tanza3D Quick Block]) |
| cultdeadcow.com  | \[ktn\] cultdeadcow.com                                             |
| Pi-hole          | \[ktn\] Pi-hole                                                     |
| pixiv.net        | \[ktn\] pixiv.net                                                   |
| reddit.com       | \[ktn\] reddit.com                                                  |
| youtube.com      | \[ktn\] youtube.com                                                 |

[Bluesky Tanza3D Quick Block]: https://github.com/Tanza3D/bluesky-quick-block

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

[`"// Userscript"` on GitHub]: https://github.com/search?q=%22%2F%2F%20%3D%3DUserScript%3D%3D%22&type=repositories
[`r/userscripts` on Reddit]: https://reddit.com/r/userscripts/
[Greasyfork]: https://greasyfork.org/
[OpenUserJS]: https://openuserjs.org
