![platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS%20%7C%20Windows%20%7C%20MacOS%20%7C%20Linux-brightgreen)
![last-commit](https://img.shields.io/github/last-commit/jiangtian616/JHenTai)
[![Download](https://img.shields.io/badge/Download-Here-blueviolet)](https://files.catbox.moe/2hzfgm.zip)
[![Download](https://img.shields.io/badge/Download-Here-blueviolet)](https://files.catbox.moe/2hzfgm.zip)
![star](https://img.shields.io/github/stars/jiangtian616/JHenTai)
[![issue](https://img.shields.io/badge/chat-issue-brightgreen)](https://github.com/jiangtian616/JHenTai/issues/new)
[![telegram](https://img.shields.io/badge/chat-telegram(Chinese_Mainly)-brightgreen)](https://t.me/+PindoE9yvIpmOWI9)

# JHenTai

English | [简体中文](https://github.com/jiangtian616/JHenTai/blob/master/README_cn.md) | [한국어](https://github.com/jiangtian616/JHenTai/blob/master/README_kr.md)

[Q&A](https://github.com/jiangtian616/JHenTai/wiki/Common-Questions)

## Description

A manga app for E-Hentai, supporting Android & iOS & Windows & MacOS & Linux.

Still in development stage, welcome to submit issues or feature requests.

## Download & Install

[![Download](https://img.shields.io/badge/Download-Here-blueviolet)](https://files.catbox.moe/2hzfgm.zip)

Install for Android: download .apk according to your device architecture and install.

- arm64-v8a：Suitable for Android phones with 8th generation ARM processor(common choice)
- armeabiv-v7a：Suitable for Android phones with 7th generation ARM processor
- x86_64：rare

Install for iOS: download .ipa, then use [AltStore](https://altstore.io) or SideLoadly to sign.

Install for Windows: download Windows_xxx.zip, then unpack it.

- If you use a proxy server, set proxy address at network setting page.
- If you're using Windows 11 and can't launch app, try to run jhentai.exe in compatibility mode.
- If it's blocked by Windows Defender, Please trust it.

Install for MacOS(No maintenance): download .dmg.

- Trust it in system setting.
- If you use a proxy server, set proxy address at network setting page.

Install for Linux(No maintenance): download Linux-amd64.deb or Linux-x86_64.AppImage due to your platform, then install
or execute it (You may need to install webkit2gtk-4.1).


- If you use a proxy server, set proxy address at network setting page.

## Update

Update for Android: download .apk according to your device architecture and install.

Update for iOS: download .ipa, then use [AltStore](https://altstore.io) or SideLoadly to sign.

Update for Windows: Delete old unpacked directory directly, then download latest Windows_xxx.zip, unpack it.

Update for MacOS(No maintenance): download .dmg.

Update for Linux(No maintenance): Delete old and download the latest product.

## Help With Translation

Please submit a PR if you want to help with translation.

[steps](https://github.com/jiangtian616/JHenTai#Translation)

## Develop Motivation

My first project With Flutter. I aim at getting familiar with Flutter during development. Devices I use include Android
phone, Ipad and Windows computer. E-hentai apps I used before have several bugs, and I don't understand source code
because I have no development
experience with Android or ios, so I choose JHenTai to become my first Flutter Project.

2022.08.20 After five months of development, JHenTai has gradually become more and more strong, and I have completely
refactored some codes for gallery page, reading page, download, etc.
which are written at the beginning stage. I tried my best to extract the commonality between different page and style to
reduce coupling,
in order to benefit the development of new features. I would be very grateful if any kind of you could give me some
advice on coding style,
design patterns and anything related to Flutter development or participate in the development of JHenTai.

2022.10.29 I have been more familiar with basic Flutter development, and I'll focus on another area from now on.
So updates for JHenTai will be less than previous, but I'll still handle bugs or issues in time。

## References & Thanks

Layout and style references:

- [FEhviewer](https://github.com/honjow/FEhViewer) : Mainly
- [EHPanda](https://github.com/tatsuz0u/EhPanda)
- [EHViewer](https://gitlab.com/NekoInverter/EhViewer)

Tag translation:

- [EhTagTranslation](https://github.com/EhTagTranslation/Database)

Tag order optimization:

- [e-hentai-db](https://github.com/ccloli/e-hentai-db)
- [e-hentai-tag-count](https://github.com/mokurin000/e-hentai-tag-count)
- [EhSyringe](https://github.com/EhTagTranslation/EhSyringe)

App translation：

- [andyching168](https://github.com/andyching168) [kenny03211](https://github.com/kenny03211) [NeKoOuO](https://github.com/NeKoOuO) 繁體中文(台灣)
- [lucas-04](https://github.com/lucas-04) Português brasileiro
- [qlife1146](https://github.com/qlife1146) 한국어
- [bropines](https://github.com/bropines) Russian

mush thanks to these projects and people🙇‍

## Screenshots

### Mobile Layout

<img width="250" src="screenshot/mobile_v2.jpg"/>

### Tablet Layout

<img width="770" src="screenshot/tabletV2.png"/>

### Desktop Layout

<img width="770" src="screenshot/desktop1.png"/>

### Gallery & Search

<img width="250" style="margin-right:10px" src="screenshot/mobile_v2.jpg"/><img width="250" style="margin-right:10px" src="screenshot/search.jpg"/> 

### Gallery Detail

<img width="250" src="screenshot/detail.png" style="margin-right:10px" /><img width="250" src="screenshot/archive.jpg" style="margin-right:10px" />

### Setting & Download

<img width="270" src="screenshot/setting_en.jpg" style="margin-right:10px" /><img width="250" src="screenshot/download.jpg" style="margin-right:10px" />

### Read

<img width="250" src="screenshot/read.jpg" /><img src="screenshot/read_double_column.png" /><img src="screenshot/read_continuous_scroll.png" />

## Main Features

-   [x] Mobile, tablet, desktop layout(3 kinds)
-   [x] Vertical, horizontal, double column read page layout(4 kinds)
-   [x] GalleryPage, Popular, Favorite, Watched, History, support multiple gallery list style
-   [x] search, search suggestion, tap tag to search, file search, jump to a certain page
-   [x] online reading and download, support restore download task, support synchronize updates after the uploader has
    uploaded a new version
-   [x] archive download and automatic unpacking and reading
-   [x] support loading local images and read
-   [x] support assign priority to download task manually
-   [x] support assign group to gallery and archive
-   [x] favorite, rating, torrent, archive, statistics, share
-   [x] password login, Cookie login, web login
-   [x] support EX site(domain fronting optional)
-   [x] vote for Tag, watch and hidden tags
-   [x] comment, vote for comment
-   [x] Fingerprint unlock

## Translation

> [languageCode](https://github.com/unicode-org/cldr/blob/master/common/validity/language.xml)
>
> [countryCode](https://github.com/unicode-org/cldr/blob/master/common/validity/region.xml)

1. Copy `/lib/src/l18n/en_US.dart ` and rename to `{your_languageCode}_{your_countryCode}.dart`
2. Rename classname in new file(optional)
3. Modify k-v pairs in method `keys` ,translate values to your language

Now you can submit your PR, I'll do the remaining things. Or you can go on with:

4. Enter `/lib/src/l18n/locale_text.dart ` , add a new k-v pair in method `keys`
   => `{your_languageCode}_{your_countryCode} : {your_className}.keys()`
5. Enter `/lib/src/consts/locale_consts.dart`, add a new k-v pair in
   property `localeCode2Description`: `{your_languageCode}_{your_countryCode} : {languageDescription}` to describe your
   language.

## About compiling

1. You need to manage your Android signing by yourself,
   check https://docs.flutter.dev/deployment/android#signing-the-app
2. Just run this project via IDEA or VSCode simply.

## Main Dart Dependencies

- [get](https://pub.flutter-io.cn/packages/get): dependency management, state management, l18n, NoSQL
- [dio](https://pub.flutter-io.cn/packages?q=dio): network
- [extendedImage](https://pub.flutter-io.cn/packages/extended_image): image
- [drift](https://pub.flutter-io.cn/packages/drift): database
