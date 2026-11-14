# Zerre

**Everything, one dot away.** Zerre is a free, calm workspace for your day: tasks, a focus timer, notes, file tools and more, in one place. It works offline, needs no account and keeps what you make on your own device. It began in the menu bar of the Mac and is now coming to every device you use.

This repository only holds the **downloads**. The source code of the app is not published. Everything else about Zerre, with pictures, is on **[zerre.app](https://zerre.app)**.

## Download

| Device | State | Where |
|---|---|---|
| **Mac** | Zerre 1.5.1, the full app | [Release v1.5.1](../../releases/tag/v1.5.1) |
| **Linux** | Zerre 0.1.0, a preview: `.deb`, `.rpm`, AppImage and an Arch package | [Release desktop-v0.1.0](../../releases/tag/desktop-v0.1.0) |
| **Windows, Android, iPhone and iPad** | Coming. Nothing to download yet | [zerre.app/download](https://zerre.app/download/) |

### Mac

Open the [Mac release](../../releases/tag/v1.5.1) and pick the file for your Mac:

* **arm64**: Apple silicon, macOS 27 or later. This is the tested one.
* **universal**: Apple silicon and Intel, macOS 15 or later. A preview: the same code compiled for older systems, not yet tested there. Live Notes needs macOS 26 or later and says so when it cannot run.

Open the disk image and drag Zerre onto the Applications folder. If macOS says it cannot verify Zerre, open System Settings, then Privacy and Security, and choose **Open Anyway** once. [zerre.app/download](https://zerre.app/download/) explains each step.

### Linux

Open the [Linux release](../../releases/tag/desktop-v0.1.0), a preview, and pick the file for your system:

* **Ubuntu, Debian and relatives**: `sudo apt install ./Zerre_0.1.0_amd64.deb` (or the `arm64` file on an ARM machine).
* **Fedora and relatives**: `sudo dnf install ./Zerre_0.1.0_amd64.rpm`.
* **Arch Linux and Omarchy**: `sudo pacman -U zerre-bin-0.1.0-1-x86_64.pkg.tar.zst`.
* **Any other recent distribution**: the AppImage. Make it executable and run it; if it says FUSE is missing, run it with `--appimage-extract-and-run`.

It was tried in test machines of Ubuntu, Debian, Fedora and Arch, not yet on a real desktop, and the files are not signed. [zerre.app/support](https://zerre.app/support/) has the details for every desktop.

## Check your download

Every release lists its checksums. In a terminal, in the folder you downloaded to, on a Mac:

```bash
shasum -a 256 -c Zerre-1.5.1-arm64.dmg.sha256
```

and on Linux:

```bash
sha256sum -c SHA256SUMS --ignore-missing
```

It should answer `OK` for the file you downloaded. The same checksums are listed on [zerre.app/download](https://zerre.app/download/).

## Licence

Zerre is free to use on your own devices under the Zerre Free Use Licence in the file `LICENSE`. It is not open source software, and its design, words and icons are protected: see [zerre.app/terms](https://zerre.app/terms/).

## Türkçe

Zerre, gününü sakin tek bir yerde toplayan ücretsiz bir çalışma alanıdır: görevler, odak sayacı, notlar, dosya araçları ve daha fazlası. Çevrimdışı çalışır, hesap istemez ve ürettiklerini kendi cihazında tutar. Mac'in menü çubuğunda başladı, şimdi kullandığın her cihaza geliyor.

Bu depo yalnızca **indirme dosyalarını** barındırır, uygulamanın kaynak kodu yayınlanmaz. Gerisi, resimleriyle birlikte, **[zerre.app/tr](https://zerre.app/tr/)** adresinde.

* **Mac**: [Zerre 1.5.1](../../releases/tag/v1.5.1). Mac'ine uyan dosyayı seç (Apple silicon ve macOS 27 için arm64, macOS 15 ve sonrası ile Intel için evrensel olan önizlemedir), diski aç ve Zerre'yi Uygulamalar klasörüne sürükle. macOS doğrulayamadığını söylerse Sistem Ayarları, Gizlilik ve Güvenlik bölümünde bir kez **Yine de Aç** de.
* **Linux**: [Zerre 0.1.0, bir önizleme](../../releases/tag/desktop-v0.1.0). `.deb`, `.rpm`, AppImage ve Arch paketi var. Ubuntu, Debian, Fedora ve Arch test makinelerinde denendi, henüz gerçek bir masaüstünde denenmedi ve dosyalar imzalı değil.
* **Windows, Android, iPhone ve iPad**: yakında. Şimdilik indirilecek bir şey yok.

## Contact

[eker600@gmail.com](mailto:eker600@gmail.com) · [zerre.app/support](https://zerre.app/support/) · [bayrameker.com](https://bayrameker.com)
