# 🇭🇺 Hungarian IPTV

A collection of Hungarian television channels in M3U playlist format.

The playlist contains Hungarian TV channels with channel logos and, where available, Electronic Program Guide (EPG) data.

## 📺 Playlist

The main playlist is:

* [`hun.m3u`](hun.m3u) — Hungarian TV channels

### Direct link

The playlist can also be used directly from GitHub:

```text
https://raw.githubusercontent.com/SilverHalo56942/huntv/main/hun.m3u
```

This URL can be added directly to a compatible IPTV player.

## 🖼️ Channel Icons

Channel logos are stored in the [`icons`](icons/) directory.

The icons are sourced from [Logopedia](https://logos.fandom.com/), a Fandom-hosted encyclopedia of brand and logo information.

All trademarks, logos, and related visual assets belong to their respective owners.

## 📡 EPG

A large portion of the channels includes EPG (Electronic Program Guide) data.

The EPG data is provided by the Hungarian section of [EPGShare](https://epgshare01.online/).

EPG availability may vary between channels and can change over time.

## ▶️ Recommended Players

### 🪟 Windows

[**IPTVnator**](https://4gray.github.io/iptvnator/) is the recommended IPTV player for Windows.

It supports M3U playlists and EPG data and provides a convenient interface for browsing and watching the channels.

Add the following playlist URL to IPTVnator:

```text
https://raw.githubusercontent.com/SilverHalo56942/huntv/main/hun.m3u
```

### 📺 Android / Android TV

[**IPTV**](https://play.google.com/store/apps/details?id=ru.iptvremote.android.iptv) by **Alexander Sofronov** is the recommended application for Android and Android TV.

Add the following playlist URL to the application:

```text
https://raw.githubusercontent.com/SilverHalo56942/huntv/main/hun.m3u
```

### Other Players

The playlist should also work with other IPTV applications and media players that support standard M3U/M3U8 playlists.

## 🔄 Updates

The playlist may be updated periodically to:

* Add new channels
* Remove unavailable channels
* Update stream URLs
* Update channel metadata
* Add or update channel icons
* Update EPG information

Stream availability is not guaranteed and may change without notice.

## 🐛 Reporting Issues

If you find a broken stream, incorrect channel information, missing icon, or another issue, please [open an issue](https://github.com/SilverHalo56942/huntv/issues).

When reporting a broken channel, please include:

* Channel name
* Approximate time the problem occurred
* IPTV player used
* A short description of the issue

## 🤝 Contributing

Contributions are welcome.

When submitting a pull request, please make sure that:

* The M3U syntax is valid.
* The stream URL is publicly accessible.
* Channel information is accurate.
* Existing formatting and naming conventions are followed.
* Icons are placed in the `icons` directory with the name following the naming of the others.
* EPG information is correctly referenced where applicable.

## 📁 Repository Structure

```text
huntv/
├── hun.m3u
├── icons/
│   ├── ...
│   └── ...
└── README.md
```

## ⚖️ Disclaimer

This repository is intended for informational and technical purposes.

The repository itself does not provide television subscriptions or operate the external streaming servers referenced by the playlist.

The availability and legality of individual streams may depend on their respective providers and jurisdictions. Users are responsible for ensuring that their use of the streams complies with applicable laws and the terms of the respective content providers.

Channel names, logos, program information, and other third-party materials remain the property of their respective owners.

If you are a rights holder and believe that a link or other material in this repository infringes your rights, please contact the repository maintainer.

---

**Maintained by [@SilverHalo56942](https://github.com/SilverHalo56942)**
