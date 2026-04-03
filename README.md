# Mikogram
[![Crowdin](https://badges.crowdin.net/e/a094217ac83905ae1625526d59bba8dc/localized.svg)](https://neko.crowdin.com/nekogram)  

Mikogram is a third-party Telegram client based on [Nekogram](https://github.com/Nekogram/Nekogram), with a few useful modifications.

- Channel: https://t.me/mikogramUpdates
- Feedback: https://github.com/axllr8tr/Mikogram/issues

## API, Protocol documentation

Telegram API manuals: https://core.telegram.org/api

MTProto protocol manuals: https://core.telegram.org/mtproto

## Compilation Guide

1. Download the source code (`git clone https://github.com/axllr8tr/Mikogram`)
2. Fill out `storeFile`, `storePassword`, `keyAlias`, `keyPassword` in `local.properties` to access your `release.keystore`. (OPTIONAL, FOR RELEASE BUILDS)
3. Go to https://console.firebase.google.com/, create two android apps with application IDs `dev.axllr8tr.mikogram` and `dev.axllr8tr.mikogram.beta`, turn on firebase messaging and download `google-services.json`, which should be copied into `TMessagesProj` folder.
4. Open the project in the Studio (note that it should be opened, NOT imported).
5. Fill out values in `TMessagesProj/src/main/java/dev/axllr8tr/mikogram/Extra.java` – there’s a link for each of the variables showing where and which data to obtain.
6. You are ready to compile your client!

## Localization

Mikogram is forked from Nekogram, and Nekogram is forked from Telegram, thus most locales follows the translations of Telegram for Android, check out https://translations.telegram.org/en/android/.

As for the Nekogram-specific strings, the devs use Crowdin to translate Nekogram. Join the devs at https://neko.crowdin.com/nekogram if you want to help them.
