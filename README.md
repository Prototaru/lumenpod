<p align="center">
  <img src="assets/lumenpod-app-icon.png" width="96" height="96" alt="LumenPod app icon">
</p>

<h1 align="center">LumenPod</h1>

<p align="center">
  <strong>A local media library for Mac.</strong><br>
  Organize your photos, videos and audio without moving files.<br>
  Hide and encrypt what’s private, and play encrypted videos right in the app.
</p>

<p align="center">
  <a href="https://lumenpod.app/?utm_source=github&utm_medium=readme">Website</a> ·
  <a href="#install">Download</a> ·
  <a href="https://lumenpod.app/guides?utm_source=github&utm_medium=readme">Guides</a> ·
  <a href="https://lumenpod.app/support?utm_source=github&utm_medium=readme">Support</a> ·
  <a href="../../issues">Issues</a>
</p>

![LumenPod library on macOS: a grid of images and videos with ratings, a tag sidebar and folder locations](assets/lumenpod-media-library.webp)

> **About this repository.** This is LumenPod's public home on GitHub: bug reports and
> feature requests. LumenPod is proprietary software — the source code is not published here.

## What LumenPod does

### Organize images, videos and audio without moving files

Add folders from your Mac and LumenPod catalogs them where they are. Your originals stay in
their folders; importing does not copy, move or encrypt anything on its own. Browse images,
videos and audio from one library, and organize them by your own tags and ratings instead of
rearranging folders.

### Catalog media on external hard drives

Add folders from external and network volumes. Unplug a drive and its media stays in the
library, marked offline, along with the drive it lives on. Plug it back in to open the files.

### Keep every copy, cover and subtitle as one item

A collected work often comes with several files. Keep them together as one item: for a film,
the original, a lighter copy, a poster and subtitles. Choose which copy plays, merge two items
into one or split a file back out, and add a title by name before you have its file.

### Find things again

Search media, tags and folders. Rate items on a 0–100 scale, stack tags to narrow the view,
and step through what you filtered in the built-in image viewer and video/audio player.
Create collections in your own order and play them start to finish.

With a downloadable model, search photos by describing what you remember in your own
language, or find similar images. AI runs locally on your Mac. Video matches use a single
frame, not the whole video; encrypted media is excluded.

### Generate subtitles on your Mac

Turn speech in video or audio into subtitles in English, Chinese or Japanese, without
uploading your media. Generated subtitles are saved next to the media. You can also extract
or embed subtitle tracks in unencrypted videos using FFmpeg, which you install separately.

### Locally encrypted vaults

Encrypt selected files on your Mac. Each password opens its own vault, and vault keys never
leave your Mac — LumenPod servers don't hold them. Encrypted video plays inside the app. Keep a
second, still-encrypted copy of a vault on another drive, and export recovery data with a
separate key file.

You can also hide selected media from everyday browsing. Hiding controls visibility;
encryption protects file contents — they are different tools.

### Browse from another device on your network

Start **Browser & WebDAV** sharing to browse your public media from a browser or a WebDAV
client on your local network. The share is read-only and has no password, and it never
includes encrypted or hidden media. It is access, not sync: LumenPod does not synchronize
libraries between Macs.

<table>
  <tr>
    <td><img src="assets/lumenpod-media-details.webp" alt="LumenPod item details showing rating, tags and file information for an encrypted video"></td>
    <td><img src="assets/lumenpod-encrypted-video-playback.webp" alt="LumenPod built-in player playing an encrypted video with the media list on the left"></td>
  </tr>
  <tr>
    <td align="center">Details, tags and ratings</td>
    <td align="center">Encrypted video plays in the app</td>
  </tr>
</table>

## Requirements

- macOS 14 Sonoma or later
- A Mac with Apple Silicon (M1 or later). Intel Macs are not supported.
- Interface languages: English, Simplified Chinese, Traditional Chinese and Japanese.
- An internet connection for license activation and periodic license checks. Your media
  itself stays local. AI features require model downloads.

## Install

1. [Download LumenPod for macOS](https://dl.lumenpod.app/LumenPod-latest-aarch64.dmg)
   (Apple Silicon).
2. Open the disk image and drag LumenPod into **Applications**.
3. Start the **14-day free trial** from the first-launch screen: every feature, once per
   device, with no account or card. If you already own a license, enter the activation code
   from your [orders page](https://lumenpod.app/orders) in **Settings → License**.

## Pricing and licenses

- **LumenPod Pro: $29.99, one-time purchase.** No subscription; every future update included.
- One license covers up to 3 Macs you own, including local AI search with a model download.
- Refunds within 14 days, requested from your orders page — see the
  [Terms of Service](https://lumenpod.app/terms#refund-policy).
- After the trial ends or a license lapses, you can still browse, play, export, delete,
  decrypt and recover existing media, open existing vaults and extract or embed subtitles.
  Adding and editing media, creating vaults, encrypting files, AI search, local network
  sharing and browsing disconnected-drive catalogs require an active license.

Current plans and prices: [lumenpod.app/#pricing](https://lumenpod.app/?utm_source=github&utm_medium=readme#pricing).

## Privacy

- Your media is not uploaded to LumenPod servers. Encryption and decryption happen locally.
- The first-launch privacy screen shows crash reports and usage analytics enabled; you can
  switch either off before continuing, or later in **Settings → Privacy**.
- Each launch sends an anonymous count with app version, OS version, system language and
  WebView version, without a persistent identifier. No media content or file paths.
- Full details: [Privacy Policy](https://lumenpod.app/privacy).

## FAQ

**Is LumenPod open source?**
No. LumenPod is proprietary. This repository exists for public bug reports and feature
requests.

**Does it work on Intel Macs?**
No. The download is an Apple Silicon build only.

**Does it move or copy my files into a library?**
No. The direct-download app catalogs your existing folders in place. Uninstalling it does not
delete your unencrypted originals.

**What happens to my encrypted files after the trial ends?**
They stay yours. Existing vaults keep opening with their passwords without an active
license. Keep backups of your media and your recovery files either way.

**Does it sync my library between Macs?**
No. A license covers up to 3 Macs, but their libraries are separate.

More answers: [lumenpod.app/#faq](https://lumenpod.app/?utm_source=github&utm_medium=readme#faq) ·
[Help Center](https://lumenpod.app/help?utm_source=github&utm_medium=readme) ·
[Release notes](https://lumenpod.app/changelog?utm_source=github&utm_medium=readme)

## Guides

- [Catalog Media on External Hard Drives on Mac](https://lumenpod.app/guides/catalog-external-hard-drives-mac?utm_source=github&utm_medium=readme)
- [Organize Images, Videos and Audio Without Moving Files](https://lumenpod.app/guides/organize-media-without-moving-files?utm_source=github&utm_medium=readme)
- [Organize Video Versions, Cover Art and Subtitles on Mac](https://lumenpod.app/guides/organize-video-versions-subtitles-mac?utm_source=github&utm_medium=readme)
- [Share Local Media from Mac over LAN and WebDAV](https://lumenpod.app/guides/share-local-media-webdav-mac?utm_source=github&utm_medium=readme)
- [Keep Media Private on a Shared Mac](https://lumenpod.app/guides/keep-media-private-shared-mac?utm_source=github&utm_medium=readme)
- [Play Encrypted Videos on Mac](https://lumenpod.app/guides/play-encrypted-videos-mac?utm_source=github&utm_medium=readme)
- [How to Password-Lock Photos, Videos and Audio on Mac](https://lumenpod.app/guides/keep-photos-private-on-mac?utm_source=github&utm_medium=readme)

## Feedback and support

- **Bugs and feature requests:** [open an issue](../../issues/new). Include your macOS
  version and LumenPod version (Settings → About).
- **License, billing and refunds:** email [support@lumenpod.app](mailto:support@lumenpod.app).
  Never post activation codes, order numbers or your account email in a public issue.
- **Security issues:** email [support@lumenpod.app](mailto:support@lumenpod.app?subject=Security%20report)
  instead of opening a public issue.

## License

LumenPod is proprietary software. © 2026 LumenPod. All rights reserved.
Use of the app is governed by the [End User License Agreement](https://lumenpod.app/eula).
The text and images in this repository may not be reused without permission.
