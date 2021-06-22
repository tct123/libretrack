![Current version](https://img.shields.io/github/release/proninyaroslav/libretrack.svg?logo=github)
![Made with Flutter](https://img.shields.io/badge/Made%20with-Flutter-blue.svg)
[![Releases](https://img.shields.io/github/downloads/proninyaroslav/libretrack/total.svg)](https://github.com/proninyaroslav/libretrack/releases)

LibreTrack
=====================

![LibreTrack](fastlane/metadata/android/en-US/images/featureGraphic.png)

[<img alt="Get it on F-Droid" height="80" src="https://tachibanagenerallaboratories.github.io/images/badges/F-Droid/get-it-on.png">]()
[<img alt="Get it on Google Play" height="80" src="https://tachibanagenerallaboratories.github.io/images/badges/Google%20Play/google-play-badge.png">](https://play.google.com/store/apps/details?id=org.proninyaroslav.libretrack)
[<img alt="Get it on GitHub" height="80" src="https://tachibanagenerallaboratories.github.io/images/badges/GitHub/get-it-on-github.png">](https://github.com/proninyaroslav/libretrack/releases)
[<img alt="Get it on Android File Host" height="80" src="https://tachibanagenerallaboratories.github.io/images/badges/Android%20File%20Host/android-file-host-badge.png">]()
[<img alt="Direct APK Download" height="80" src="https://tachibanagenerallaboratories.github.io/images/badges/Direct%20Download/direct-apk-download.png">](https://proninyaroslav.ru/ftp/libretrack)

Private, cross-platform package tracking app.

Track postal items directly on your device using accounts of postal services. The app respects your privacy and freedom: you don't use third-party online services.

[Use, see, change and share](https://en.wikipedia.org/wiki/Free_software); [with all](https://en.wikipedia.org/wiki/Copyleft).

## 📋 Features

 - Free and Open Source software (FOSS)
 - Support for various platfroms and devices (currently Android only)
 - Support accounts of different carriers (currently UPS only)
 - Detailed information about the postal items, carriers, tracking history
 - Local push notifications
 - Automatic tracking in the background, and also manual refreshing
 - Ability to add a list of track numbers
 - Filter and sort numbers by activity date, package status, carrier, etc
 - Barcode and QR code scanner for tracking numbers
 - Archiving tracking numbers
 - Material Design 2.0
 - Night theme
 - Responsive UI for different devices form factors

## 🖥️💻📱 Available platforms

 - Android
 - ~~Linux~~ (planned)
 - ~~iOS~~ (planned)
 - ~~macOS~~ (planned)
 - ~~Web~~ (planned)
 - ~~Windows~~ (planned)

## 📦 Supported postal services

[![UPS](assets/service_logo/ups.png)](https://www.ups.com)

## 🌍 Translations

 - **English**
 - **Russian**

## 💰 Donation

If you like LibreTrack you can support developer with these methods. If you have problems with payment or you want to donate in another way, contact me: `proninyaroslav@mail.ru`. Thank you!

 - **PayPal**: [![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=GWWYZSCKPAB2Q)
 - **Yandex Money (YooMoney)**: `410011738561939`
 - **WebMoney**:
     - **WMZ**: `Z335461926163`
     - **WMR**: `R151579576467`
 - **Amazon.com eGift Cards**: just choose your amount and type e-mail `proninyaroslav@mail.ru`
in the gift card details https://smile.amazon.com/gp/product/B004LLIKVU/
 - **Liberapay**: [![liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/proninyaroslav/donate)
 - **Bitcoin**: `1Af9DgxtWvVp6bFiYQw2MeWtRzTXshRYpB`
 - **Nano**: `nano_1b13t35x5dwu39xcs3xj4ozfsniozfnxdqwjijy6efnkda6sc3hqie914fja`

## ⚙️ Building

To build, you need to install [Flutter](https://flutter.dev/docs/get-started/install).

Enter the following command in the terminal to build the project:
 - Android APK
   ```
   flutter build apk --flavor main
   ```
   You can also split APK into different architectures:
   ```
   flutter build apk --flavor main --split-per-abi
   ```
   or
   ```
   flutter build apk --flavor main --target-platform [android-arm|android-arm64|android-x64]
   ```
   The built APK will be located in the `build/app/outputs/flutter-apk/` directory.

## 🎉 Contributing

Please see [CONTRIBUTING.md](CONTRIBUTING.md)

#### Developers

* [Yaroslav Pronin](https://github.com/proninyaroslav)

#### Logo

* [Ramy (@rshirwan)](https://t.me/rshirwan)

## Screenshots

![phone](art/screenshots/phone.png) ![phone dark](art/screenshots/phone_dark.png) ![tablet](art/screenshots/tablet.png)

## 🔒 Privacy Policy

Please see our [Privacy Policy](PRIVACY.md).

## 📄 License

[![Large GPLv3 logo with “Free as in Freedom”](https://www.gnu.org/graphics/gplv3-with-text-136x68.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)

    Copyright (C) 2021 Yaroslav Pronin <proninyaroslav@mail.ru>
    Copyright (C) 2021 Insurgo Inc. <insurgo@riseup.net>
    This file is part of LibreTrack.
    LibreTrack is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
