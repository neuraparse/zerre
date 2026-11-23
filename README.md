# Zerre

Zerre is a desktop assistant for files, notes, tasks and focus. This repository distributes the app. Installation instructions are available in [English](https://zerre.app/download/) and [Türkçe](https://zerre.app/tr/download/).

| Device | Download | Choose a package |
| --- | --- | --- |
| Mac | [Mac App Store](https://apps.apple.com/app/id6832377467) · [Direct download 1.6.0](https://github.com/neuraparse/zerre/releases/tag/v1.6.0) | Apple silicon on macOS 27 or later, or the universal preview for Intel and Apple silicon on macOS 15 or later |
| Windows | [Desktop preview 0.2.0](https://github.com/neuraparse/zerre/releases/tag/desktop-v0.2.0) | x64 for Intel and AMD or ARM64 for Windows on Arm. Offline installers include Microsoft Edge WebView2 |
| Linux | [Desktop preview 0.2.0](https://github.com/neuraparse/zerre/releases/tag/desktop-v0.2.0) | Deb, RPM and AppImage for x86-64 and ARM64. Arch Linux and Omarchy also have an x86-64 pacman package |
| Browser | [Open Zerre](https://zerre.app/app/) | The browser edition works offline after the first visit |

## Verify a download

Download the package, its release’s **SHA256SUMS** and **SHA256SUMS.sig**, and the [release signing key file](https://raw.githubusercontent.com/neuraparse/zerre/main/release-signers). The signing key is listed on [the publisher’s GitHub account](https://github.com/neuraparse.keys) and has the ED25519 fingerprint `SHA256:/KRyWtuAz5IzM5B/EDhlbCQ97hz2VDdoluzuG8iFqXo`.

Verify the signature with OpenSSH in a shell that supports input redirection. On Windows, Command Prompt also supports this command.

```sh
ssh-keygen -Y verify -f release-signers -I neuraparse -n file -s SHA256SUMS.sig < SHA256SUMS
```

Then compare the SHA-256 of the file you downloaded to the matching line in the verified list. Use `shasum -a 256 FILENAME` on macOS, `sha256sum FILENAME` on Linux, or `Get-FileHash FILENAME -Algorithm SHA256` in PowerShell.

Download the [Fedora signing key](https://github.com/neuraparse/zerre/releases/download/desktop-v0.2.0/Zerre-RPM-GPG-KEY.asc), verify its SHA-256 against the signed list, and import it with `sudo rpmkeys --import ./Zerre-RPM-GPG-KEY.asc` before installing the RPM. Its OpenPGP fingerprint is `25AB DF01 416F 34A0 441E A097 00FC E97E 6AB9 AC58`.

The direct Mac applications carry ad hoc signatures and have no Apple notarization. Windows preview installers have no Authenticode publisher certificate. The Mac App Store handles installation and updates for the store edition.

## Türkçe

Mac’te ilk seçenek [Mac App Store](https://apps.apple.com/app/id6832377467). Doğrudan indirmek için [Mac 1.6.0 sürümünü](https://github.com/neuraparse/zerre/releases/tag/v1.6.0) veya [Windows ve Linux 0.2.0 önizlemesini](https://github.com/neuraparse/zerre/releases/tag/desktop-v0.2.0) aç. Her iki sürümde de yayıncı anahtarıyla imzalanmış SHA-256 listesi bulunur. Cihazına uygun paketi ve kurulum adımlarını [Türkçe indirme sayfasında](https://zerre.app/tr/download/) bulabilirsin.

## Contact

[zerre.app](https://zerre.app) · [Support](https://zerre.app/support/) · [bayrameker.com](https://bayrameker.com)
