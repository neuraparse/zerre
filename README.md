# Zerre

**Everything, one dot away.** Zerre is a free menu bar workspace for the Mac: tasks, a focus timer, clipboard history, Markdown notes, tidy ups that show their plan first, file tools, live captions and a look at your Mac's health, all in one calm place. It works offline, needs no account and keeps what you make on your Mac.

This repository only holds the **downloads**. The source code of the app is not published. Everything else about Zerre, with pictures, is on **[zerre.app](https://zerre.app)**.

## Download

Open the [latest release](../../releases/latest) and pick the file for your Mac:

* **arm64**: Apple silicon, macOS 27 or later. This is the tested one.
* **universal**: Apple silicon and Intel, macOS 15 or later. A preview: the same code compiled for older systems, not yet tested there. Live Notes needs macOS 26 or later and says so when it cannot run.

Open the disk image and drag Zerre onto the Applications folder. If macOS says it cannot verify Zerre, open System Settings, then Privacy and Security, and choose **Open Anyway** once. [zerre.app/download](https://zerre.app/download/) explains each step.

## Check your download

Every file has a checksum next to it. In Terminal, in the folder you downloaded to:

```bash
shasum -a 256 -c Zerre-1.5.0-arm64.dmg.sha256
```

It should answer `OK` (use the file name of the version you downloaded). The same checksums are listed on [zerre.app/download](https://zerre.app/download/).

## Licence

Zerre is free to use on your own Macs under the Zerre Free Use Licence in the file `LICENSE`. It is not open source software, and its design, words and icons are protected: see [zerre.app/terms](https://zerre.app/terms/).

## Türkçe

Zerre, Mac için ücretsiz bir menü çubuğu çalışma alanıdır: görevler, odak sayacı, pano geçmişi, Markdown notlar, önce planını gösteren temizlikler, dosya araçları, canlı altyazı ve Mac'inin sağlığına bir bakış, hepsi tek yerde. Çevrimdışı çalışır, hesap istemez ve ürettiklerini Mac'inde tutar.

Bu depo yalnızca **indirme dosyalarını** barındırır, uygulamanın kaynak kodu yayınlanmaz. Gerisi, resimleriyle birlikte, **[zerre.app/tr](https://zerre.app/tr/)** adresinde. İndirmek için [son sürüme](../../releases/latest) git, Mac'ine uyan dosyayı seç, diski aç ve Zerre'yi Uygulamalar klasörüne sürükle. macOS doğrulayamadığını söylerse Sistem Ayarları, Gizlilik ve Güvenlik bölümünden bir kez **Yine de Aç**'ı seç.

## Contact

[eker600@gmail.com](mailto:eker600@gmail.com) · [zerre.app/support](https://zerre.app/support/) · [bayrameker.com](https://bayrameker.com)
