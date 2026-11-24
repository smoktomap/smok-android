# Smok: smoking areas in Japan (Android APK)

**Smok is a free Android app with a map of smoking areas and smoking rooms in Japan.** Find the nearest smoking room at a station, airport or shopping mall, a municipal smoking area, or a cafe where smoking is allowed, in 13 languages. No ads, no in-app purchases, and the map works without an account.

<p>
  <a href="https://play.google.com/store/apps/details?id=to.smok.app"><img alt="Smok on Google Play" src="https://img.shields.io/badge/Google%20Play-to.smok.app-1a73e8?style=for-the-badge&logo=googleplay&logoColor=white"></a>
  <a href="https://smok.to"><img alt="smok.to" src="https://img.shields.io/badge/Web-smok.to-1a73e8?style=for-the-badge"></a>
  <a href="https://github.com/smoktomap/smok-android/releases/latest"><img alt="Download the APK" src="https://img.shields.io/badge/Download-APK-1557b0?style=for-the-badge&logo=android&logoColor=white"></a>
</p>

> This is the **Smok Japan smoking map** (package `to.smok.app`, [smok.to](https://smok.to)), not the vape brand of the same name.

## Download the Smok APK

**[Download smok-universal.apk](https://github.com/smoktomap/smok-android/releases/latest/download/smok-universal.apk)** (about 169 MB, works on every Android phone, always the latest version). It is the same build as on [Google Play](https://play.google.com/store/apps/details?id=to.smok.app), signed with Google Play's key, so it also installs over a Play copy.

- Package name: `to.smok.app`
- Android 8.0 or newer; works on phones without Google Play services.

### Smaller files for your phone's CPU (optional)

On the [Releases](https://github.com/smoktomap/smok-android/releases) page there are also smaller APKs, one per CPU architecture: `arm64-v8a` (most phones of the last years, about 54 MB), `armeabi-v7a` (older 32-bit phones, about 41 MB), `x86_64` and `x86` (emulators, Chromebooks). **They are signed with a different key than the Google Play build**, so they cannot be installed over a Play copy (uninstall it first) and the other way round. If you are not sure, take `smok-universal.apk`.

### Install

1. Open the downloaded `.apk` on the phone.
2. If Android asks, allow installing from the app you opened it with (your browser or file manager). You can turn that off again afterwards.
3. Open Smok. The map works without an account.

### Follow updates with Obtainium

1. In [Obtainium](https://github.com/ImranR98/Obtainium) tap **Add app** and paste `https://github.com/smoktomap/smok-android` (or open `obtainium://add/https://github.com/smoktomap/smok-android` on the phone).
2. Obtainium asks **Pick an APK**. Choose **`smok-universal.apk`**: it is the Google Play build and keeps updating the same way. Obtainium pre-selects the file for your CPU (for example `smok-1.0.3-arm64-v8a.apk`), which has the other signature: change it unless you want that one.
3. To skip the question for good, before tapping Add open **APK selection**, put `smok-universal` into **Filter links by regex**.

Checked with Obtainium 1.7.5 on Android 16.

## What Smok shows

- **Smoking rooms at stations, airports and shopping malls**: which floor, which side of security, how precise the pin is, opening hours.
- **Municipal smoking areas** that the city itself lists, with the page the information came from.
- **Smoking cafes** and other places that confirm smoking is allowed.
- **Search** by place, station or category, and a *Nearest* button for when you are standing in the street.
- **Street-smoking ban zones** drawn on the map for the wards and cities where they apply.
- **13 languages**: 日本語, English, 한국어, 繁體中文, ไทย, Tiếng Việt, Bahasa Indonesia, Español, Italiano, Deutsch, Français, Русский, Português.

Information is published only when an official source (the operator's own page or map, or the municipality's own list) confirms it. A place that is not confirmed stays off the map, and an empty list means *we have not checked*, not *there is nowhere to smoke*. Please follow local rules and signs.

## 日本語

**Smok（スモーク）は、日本全国の喫煙所・喫煙室を地図で探せる無料のAndroidアプリです。** 近くの喫煙所・喫煙室を地図で検索でき、路上喫煙禁止エリアも表示します。駅・空港・商業施設に対応しています。APKは上の「Download smok-universal.apk」から入手できます（Google Playと同じビルドです）。

## 한국어

**Smok은 일본 흡연구역과 흡연실을 지도에서 찾을 수 있는 무료 안드로이드 앱입니다.** 길거리 흡연 금지 구역도 한눈에 확인할 수 있습니다. APK는 위의 Download smok-universal.apk에서 받을 수 있습니다(Google Play와 같은 빌드).

## 繁體中文

**Smok 是免費的 Android 應用程式，可在地圖上找日本的吸菸區與吸煙室**，並標示路上禁菸區域，一鍵找到最近的地點。APK 可由上方的 Download smok-universal.apk 下載（與 Google Play 為同一版本）。

## Versions

| Version | Notes |
|---|---|
| 1.0.3 | Finds where you are when it opens (if location is already allowed), location without Google Play services, airport rooms show which side of security they are on, street-smoking ban notice, fixes. |

## Contact

[contact@smok.to](mailto:contact@smok.to) · [smok.to](https://smok.to) · The app itself is closed source; this repository holds the release builds only.
