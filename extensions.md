# Browser Mods

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

### Safari

Some notes:

- This configuration is duplicated in Safari Technology Preview as well.
- Extensions for PWAs are only available on macOS. PWAs on iOS and iPadOS lack this feature (for now?).

The following table details which extensions are enabled for which Safari Profiles.

| Extension                                   | Main | Bluesky | GitHub | Mastodon | Twitch | YouTube |
| ------------------------------------------- | ---- | ------- | ------ | -------- | ------ | ------- |
| 1Password                                   | x    | x       | x      | x        | x      | x       |
| Auto Reload                                 |      |         |        |          | x      |         |
| DeArrow for YouTube                         |      |         |        |          |        | x       |
| IINA "Open in IINA"<sup>†</sup>             |      |         |        |          |        |         |
| Keyword Search                              | x    | x       | x      | x        | x      | x       |
| NetNewsWire "Subscribe to Feed"<sup>†</sup> |      |         |        |          |        |         |
| Refined GitHub                              |      |         | x      |          |        |         |
| StopTheMadness Pro                          | x    | x       | x      | x        | x      | x       |
| Tampermonkey                                | x    | x       | x      | x        | x      | x       |
| Velja "Velja"<sup>†</sup>                   | x    | x       | x      | x        | x      | x       |
| Wipr 2 "Blocklist 1"                        | x    | x       | x      | x        | x      | x       |
| Wipr 2 "Blocklist 2"                        | x    | x       | x      | x        | x      | x       |
| Wipr 2 "Blocklist 3"                        | x    | x       | x      | x        | x      | x       |
| Wipr 2 "Blocklist 4"                        | x    | x       | x      | x        | x      | x       |
| Wipr 2 "Wipr Extra"                         | x    | x       | x      | x        | x      | x       |

<sup>†</sup>: Extension is included with its associated application and cannot be individually removed.

## Userscripts

| Top-Level Domain | Userscript Name                                                     |
| ---------------- | ------------------------------------------------------------------- |
| *                | \[ktn\] <all_urls>                                                  |
| *                | Double-click Image Downloader                                       |
| *~700 domains*   | Bypass All Shortlinks Debloated                                     |
| *~355 domains*   | tinyShield                                                          |
| *~100 domains*   | Bypass Paywalls Clean - en                                          |
| *~5 domains*     | Stop videos looping                                                 |
| *~3 domains*     | CRX Downloader                                                      |
| backloggd.com    | \[ktn\] backloggd.com                                               |
| bitbang.social   | \[ktn\] bitbang.social                                              |
| bitbang.social   | TangerineUI for Mastodon                                            |
| bsky.app         | \[ktn\] Bluesky Quick Block (fork of [Bluesky Tanza3D Quick Block]) |
| bsky.app         | Block button in dropdown                                            |
| cultdeadcow.com  | \[ktn\] cultdeadcow.com                                             |
| google.com       | View Image                                                          |
| instagram.com    | IG Helper                                                           |
| Pi-hole          | \[ktn\] Pi-hole                                                     |
| pixiv.net        | \[ktn\] pixiv.net                                                   |
| reddit.com       | \[ktn\] reddit.com                                                  |
| spotify.com      | spotdl-interact-web                                                 |
| spotify.com      | Spotify Enhancer (Full-Sized Cover Art Downloader)                  |
| spotify.com      | Spotify Enhancer (Spotify to YouTube)                               |
| telegram.org     | Telegram Media Downloader                                           |
| twitch.tv        | FrankerFaceZ                                                        |
| xbox.com         | Better xCloud                                                       |
| youtube.com      | \[ktn\] youtube.com                                                 |
| youtube.com      | Simple youTube Age Restriction Bypass                               |
| youtube.com      | YouTube: CPU Tamer                                                  |

[Bluesky Tanza3D Quick Block]: https://github.com/Tanza3D/bluesky-quick-block
