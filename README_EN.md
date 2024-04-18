<div align="center">
   <h1>MIUI Quality of Life Improvement</h1>
   <p>
       <b>English  丨 <a href="https://github.com/Xposed-Modules-Repo/io.github.chsbuffer.miuihelper/blob/main/README.md">简体中文</a></b>
   </p>
   <a href="https://t.me/miuiqol"><img alt="Telegram Group" src="https://img.shields.io/badge/Join-Telegram-blue.svg?logo=telegram"></a>
</div>

## Description

This module improves my experience of MIUI 12 to 14 and HyperOS. Details about each feature are in the module's settings.

⭐ Proudly powered by [DexKit](https://luckypray.org/DexKit/en/), a high-performance dex runtime parsing library.

## Features
- Security app
  - Enable "App Behavior Record" (on Global ROM)
  - "App Behavior Record" includes System apps' records (no more needed for HyperOS)
  - Allow restrict System apps' WLAN usage
  - Replace App Info "Clear defaults" with "Open by default" setting
  - Ignore the countdown and click 'confirm' to skip the risky setting warning page.
  - Banner score lock at 100 points
- System Launcher
  - Don't hide Google App shortcut (on China ROM)¹
  - Enable "-1 Screen Picker" (between "App Vault" and "Google Feed") (on China ROM)¹
  - Replace "Global Search" with "Google Search"¹
- SystemUI
  - Don't hide "Nearby Sharing" from Control Center²
  - Don't hide "Google Wallet" from Control Center²
  - Remove notification settings whitelist (on China ROM)
  - Notification's "More Info" redirect to the corresponding notification channel setting (broken on Android 14)
- Screenshot
  - Save screenshots to `Pictures/Screenshots`
- ScreenRecorder
  - Save videos to `Movies/ScreenRecorder`
  - Force enable "Native Audio Recorder"
- Mi AI Translator
  - Force enable AI subtitles (which can translate or transcribe between Chinese and English)
- Updater
  - Remove OTA validate

Notes:

1. [Google App](https://play.google.com/store/apps/details?id=com.google.android.googlequicksearchbox) is required.
2. On China ROM, some features of Google Mobile Services are disabled. To use these features, System modification is required. Refer to Unlock CN GMS
 Magisk Module: [https://github.com/fei-ke/unlock-cn-gms](https://github.com/fei-ke/unlock-cn-gms) for more information.