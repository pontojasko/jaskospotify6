<p align="center"><img src="Resources/Icon@2x.png" width="96" alt="JaskoSpotify icon"></p>

<h1 align="center">JaskoSpotify</h1>

<p align="center"><b>Spotify, back on iOS 5 and 6.</b><br>A native standalone client for jailbroken iOS 5 and 6, on iPhone, iPod touch, and iPad.</p>

---

JaskoSpotify brings your Spotify account to iOS 5 and 6: your library, playlists, queue, and offline music. The app runs on the device and uses your existing account.

JaskoSpotify is based on [Spotify6](https://github.com/iKiWY/Spotify6), which is itself based on [riff](https://github.com/SecondTrack/riff) by Second Track. riff provided the Spotify connection and audio playback foundation; Spotify6 developed that foundation into a native client for iOS 5 and 6. We are grateful to both projects and their contributors.

<table align="center">
  <tr>
    <td align="center" valign="top"><b>Home</b><br><img src="docs/screenshots/home.png" width="190" alt="Home"></td>
    <td align="center" valign="top"><b>Now playing</b><br><img src="docs/screenshots/player.png" width="190" alt="Now playing"></td>
    <td align="center" valign="top"><b>Queue</b><br><img src="docs/screenshots/queue.png" width="190" alt="Playback queue"></td>
    <td align="center" valign="top"><b>Album</b><br><img src="docs/screenshots/album.png" width="190" alt="Album page"></td>
  </tr>
  <tr>
    <td align="center" valign="top"><b>Track menu</b><br><img src="docs/screenshots/menu.png" width="190" alt="Track menu"></td>
    <td align="center" valign="top"><b>Search</b><br><img src="docs/screenshots/search.png" width="190" alt="Search"></td>
    <td align="center" valign="top"><b>Artist</b><br><img src="docs/screenshots/artist.png" width="190" alt="Artist page"></td>
    <td align="center" valign="top"><b>Notification Center</b><br><img src="docs/screenshots/widget.png" width="190" alt="Notification Center widget"></td>
  </tr>
</table>

### On iPad

The app is universal. On iPad, it has its own layout with a sidebar, playback controls along the bottom, and a full-screen player. It works in both portrait and landscape.

<table align="center">
  <tr>
    <td align="center" valign="top"><b>Home (portrait)</b><br><img src="docs/screenshots/ipad-home-portrait.png" width="300" alt="iPad Home in portrait"></td>
    <td align="center" valign="top"><b>Home (landscape)</b><br><img src="docs/screenshots/ipad-home-landscape.png" width="400" alt="iPad Home in landscape"></td>
  </tr>
  <tr>
    <td align="center" valign="top"><b>Player (portrait)</b><br><img src="docs/screenshots/ipad-player-portrait.png" width="300" alt="iPad player in portrait"></td>
    <td align="center" valign="top"><b>Player and queue (landscape)</b><br><img src="docs/screenshots/ipad-player-queue-landscape.png" width="400" alt="iPad player and queue in landscape"></td>
  </tr>
  <tr>
    <td align="center" valign="top"><b>Playlist (landscape)</b><br><img src="docs/screenshots/ipad-playlist-landscape.png" width="400" alt="iPad playlist in landscape"></td>
    <td align="center" valign="top"><b>Album (landscape)</b><br><img src="docs/screenshots/ipad-album-landscape.png" width="400" alt="iPad album in landscape"></td>
  </tr>
</table>

### Classic iOS look

Choose between the dark Spotify-inspired theme and Classic iOS, inspired by the system apps in iOS 6.

<table align="center">
  <tr>
    <td align="center" valign="top"><b>Home</b><br><img src="docs/screenshots/classic-ios/iphone-home.png" width="190" alt="Classic theme: Home"></td>
    <td align="center" valign="top"><b>Now playing</b><br><img src="docs/screenshots/classic-ios/iphone-player.png" width="190" alt="Classic theme: player"></td>
    <td align="center" valign="top"><b>Album</b><br><img src="docs/screenshots/classic-ios/iphone-album.png" width="190" alt="Classic theme: album"></td>
  </tr>
</table>

<table align="center">
  <tr>
    <td align="center" valign="top"><b>iPad Home</b><br><img src="docs/screenshots/classic-ios/ipad-home.png" width="400" alt="Classic theme: iPad Home"></td>
    <td align="center" valign="top"><b>iPad playlist</b><br><img src="docs/screenshots/classic-ios/ipad-playlist.png" width="400" alt="Classic theme: iPad playlist"></td>
  </tr>
  <tr>
    <td align="center" valign="top" colspan="2"><b>iPad player</b><br><img src="docs/screenshots/classic-ios/ipad-player.png" width="400" alt="Classic theme: iPad player"></td>
  </tr>
</table>

> [!IMPORTANT]
> JaskoSpotify is an independent project and is not affiliated with Spotify. It uses undocumented Spotify interfaces with your own account. This may violate Spotify's Terms of Use, and the app may stop working if Spotify changes its services. Spotify Premium is required. Use it at your own risk.

## Features

### Library and discovery

- Home shows recently played playlists, albums, artists, and tracks, including plays from this device.
- Search for tracks, albums, artists, and public playlists, with recent searches. Search requires your own free Spotify developer API key.
- Artist, album, and playlist pages with optional large cover art.
- Official artwork for Spotify-made playlists such as Blends and Your Top Songs.
- Library with Liked Songs and playlists. Create playlists, add tracks, rename your playlists, and save or remove playlists from your library.
- Play entire playlists, including those with more tracks than the first loaded page.

### Player and queue

- Quick start: tracks begin playing while the rest of the audio loads; a green line shows loading progress.
- Queue with “Next in queue” and “Next up”: drag to reorder, swipe to add or remove, and choose whether playback stops at the end.
- Repeat queued tracks and continuous “Next up” playback can be controlled from the queue screen.
- Mini player with a swipe gesture to skip; full player that can be dismissed by dragging down.
- Gapless playback, preparing the next track before the current one ends.
- Native 10-band graphic equalizer with per-band frequency controls, preamp, and options to disable or flatten the bands.
- Separate streaming and download quality settings for Wi-Fi and mobile data: 96, 160, or 320 kbps. Mobile downloads can also be turned off.
- Spotify dark or Classic iOS theme; a dedicated iPad layout for portrait and landscape; support for the 4-inch iPhone 5 and iPod touch 5 displays.
- Cover Flow when rotating iPhone; on iPad, available from the sidebar.

### Offline and downloads

- Save playlists, albums, and individual tracks for offline listening. Downloads can resume and continue in the background when enabled.
- The Downloads screen shows queued and saved tracks. Pause, resume, or cancel the remaining queue; completed tracks stay on the device.
- Downloads can wait for Wi-Fi when mobile download quality is set to “Off”.
- A cache of up to 500 MB keeps recently played tracks available for replay without downloading the audio again.
- Clear all offline downloads or clear the cache separately.
- **Experimental — save mobile streams to Downloads:** when enabled in Settings, tracks streamed over mobile data are also added to the download queue at the selected mobile download quality. This uses additional mobile data and device storage. Set mobile download quality to “Off” to skip automatic saving.
- **Experimental — rotating Liked Songs downloads:** the app can download randomly selected liked tracks and refresh that set daily, one track at a time. Old tracks are removed as replacements finish downloading, while manually downloaded tracks and tracks shared with other downloads are preserved. Configure repeat behavior and the daily limit in Settings. The limit can be unlimited while keeping at least 256 MB free, or set to 256 MB, 512 MB, or 1 GB.

### Integrations and account

- Optional Notification Center widget with cover art, track, playback context (“Playing from…”), and controls. It can be disabled in Settings; widgets are not supported on iPad with iOS 5.
- Optional Last.fm integration to send qualifying plays to your profile. Offline plays are queued and submitted when connectivity returns.
- Sign in with a code at [spotify.com/pair](https://spotify.com/pair); you never enter your Spotify password in the app. The session is stored in the app's private folder and renews automatically.
- Diagnostics in Settings to help investigate connection or playback issues.

## Requirements

| | Requirement |
|---|---|
| Device | ARMv7 iPhone, iPod touch, or iPad running iOS 5 or 6 with jailbreak, including iPhone 5 and iPod touch 5. Tested on an iPhone 3GS with iOS 6, and on an iPad 1 and iPod touch 3G with iOS 5.1.1 in an emulator. |
| Installation | AppSync; JaskoSpotify installs as a regular app. |
| Account | Spotify Premium. |
| Search | Your own free Spotify developer key. The app guides you through setup. |
| Last.fm | Optional. Configure your own API credentials when building; see below. |

## First sign-in

JaskoSpotify **never asks for your password**. On first launch, it displays a short code. Enter it at [spotify.com/pair](https://spotify.com/pair) on another device to authorize your account.

## Building

Requires [Theos](https://theos.dev) and the iPhoneOS 9.3 SDK. The app has an iOS 5.0 deployment target and builds for iOS 5 and 6 with `-Werror`.

```sh
# Download the official Mbed TLS release, verify its SHA-256, and build for ARMv7
vendor/mbedtls/fetch.sh
vendor/mbedtls/build.sh

# Build a release IPA and install over USB (ideviceinstaller + AppSync)
scripts/install.sh
```

A plain `gmake package` creates a development build with an extra test hook (`music/App/MMDebug.m`) for controlling the app over SSH. Release builds leave out this hook.

### Last.fm

To enable Last.fm, copy `music/Spot/MMLastFMAppConfig.h.example` to `music/Spot/MMLastFMAppConfig.local.h` and fill in your Last.fm API key and secret. The local file is ignored by Git. Then build the app and connect your account from the Last.fm section in Settings.

### Notification Center widget

The widget in `widget/` is optional. Build it with `gmake package FINALPACKAGE=1` from that directory, install the `.deb` on the device with `dpkg -i`, respring, and enable it in iOS Settings → Notifications. It can also be disabled in the app.

### Playlist verification

See the [playlist verification checklist](docs/playlist-verification.md) for device checks covering pagination, large queues, library changes, account write failures, and offline behavior.

## How it works

JaskoSpotify signs in to a Spotify access point in a way similar to Spotify's own clients and keeps the connection open for metadata and the keys needed to play each track. The library uses the same internal services as the official apps; only search uses the public Web API and your developer key.

Tracks are fetched in encrypted form from Spotify's CDN, decrypted on the device, and decoded from Ogg Vorbis in software. Audio quality depends on the selected streaming and download settings. Since iOS 5 and 6 can no longer establish secure connections to some current services, the app bundles Mbed TLS with certificate verification for HTTPS traffic.

The widget is a small SpringBoard plugin: it reads the system's current playback information and sends playback commands like those on the Lock screen.

## Credits

JaskoSpotify is based on **[Spotify6](https://github.com/iKiWY/Spotify6)**, which built a native iOS 5 and 6 client on top of **[riff](https://github.com/SecondTrack/riff) by Second Track**. riff made Spotify playback on iOS 6 possible and provided the original protocol work and audio pipeline. Thank you to the authors and contributors of both Spotify6 and riff for this foundation.

- [stb_vorbis](https://github.com/nothings/stb) by Sean Barrett: Ogg Vorbis decoding (public domain / MIT).
- [Mbed TLS](https://github.com/Mbed-TLS/mbedtls): TLS (Apache 2.0).
- Shannon cipher, ported from rust-shannon in [librespot](https://github.com/librespot-org/librespot) (MIT).
- The audio equalizer approach was inspired by [StreamingKit](https://github.com/tumtumtum/StreamingKit) by Thong Nguyen.
- [Material Icons](https://github.com/google/material-design-icons), the `music_note` app icon (Apache 2.0).

See [NOTICE](NOTICE) for more details.

## License

GNU GPL v3.0. See [LICENSE](LICENSE).

Spotify is a trademark of Spotify AB. iPhone and iOS are trademarks of Apple Inc. JaskoSpotify is not affiliated with, sponsored by, or endorsed by Spotify or Apple.
