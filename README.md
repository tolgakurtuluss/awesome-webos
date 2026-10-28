# Awesome WebOS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated applications, launchers, homebrew tools, and development resources for webOS TVs.

> ⚠️ **Before you install anything:** Most tools on this list are unofficial community projects. Read [SAFETY.md](SAFETY.md) first, because some of them require Developer Mode or root access and can affect your TV's security, stability, or support status.

> 🌱 All contributions and PR's are welcome! You can support this repo by giving a star, too! ⭐
## Contents

- [Getting started](#getting-started)
- [Apps](#apps)
    - [Media and streaming](#media-and-streaming)
    - [Games and game streaming](#games-and-game-streaming)
    - [Ambilight and lighting](#ambilight-and-lighting)
    - [Screensavers](#screensavers)
    - [TV utilities](#tv-utilities)
    - [Privacy and debloating](#privacy-and-debloating)
    - [Launchers and home screens](#launchers-and-home-screens)
    - [Rooting and recovery](#rooting-and-recovery)
    - [Remote control](#remote-control)
    - [Community](#community)

## Getting started

### What is webOS?

webOS is a Linux-based operating system that runs apps built with web technologies. LG acquired it from HP in 2013 and uses it as the platform for its smart TVs. See [webOS on Wikipedia](https://en.wikipedia.org/wiki/WebOS) for the background.

All LG TVs released from 2015 onward, plus some 2014 models, run webOS. A few third-party brands also use it. Features, supported apps, and available tools depend on your TV's model year and webOS version, so check your exact model before trying anything on this list.

### Official resources

- [webOS TV Developer](https://webostv.developer.lge.com/) - LG's official developer portal with documentation, SDK tools, and guides for building webOS TV apps.
- [Developer Mode app guide](https://webostv.developer.lge.com/develop/getting-started/developer-mode-app) - Official instructions for installing and using the Developer Mode app to install, debug, and test apps on your TV.
- [LG Content Store](https://us.lgappstv.com/) - The official app store on your TV, where you can find the Developer Mode app by searching for "Developer Mode".

To use the official Developer Mode, you need a free LG Developer account and the Developer Mode app installed on your TV. The older webOS IDE is no longer supported, so LG now recommends the webOS TV CLI and the webOS TV extension for VS Code.

### Community resources

- [webOS Homebrew Channel](https://github.com/webosbrew/webos-homebrew-channel) - Unofficial app catalog and package manager for LG webOS TVs. ![Stars](https://img.shields.io/github/stars/webosbrew/webos-homebrew-channel?style=flat-square)


- [webOS Device Manager](https://github.com/webosbrew/dev-manager-desktop) - Desktop app for managing webOS devices and Developer Mode. ![Stars](https://img.shields.io/github/stars/webosbrew/dev-manager-desktop?style=flat-square)

- [Homebrew Channel Updater](https://repo.webosbrew.org/apps/org.webosbrew.safeupdate/) - Keeps the Homebrew Channel up to date.


## Media and streaming

- [Kodi](https://repo.webosbrew.org/apps/org.xbmc.kodi/) - Open-source media player and entertainment hub. The catalog lists webOS 4.0 or later as a requirement.

- [Jellyfin](https://github.com/jellyfin/jellyfin-webos) - webOS client for Jellyfin Server.
![Stars](https://img.shields.io/github/stars/jellyfin/jellyfin-webos?style=flat-square)

- [Moonfin](https://github.com/Moonfin-Client/Smart-TV) - Enhanced Jellyfin client for LG webOS and Samsung Tizen TVs. Built with the Enact/Sandstone framework.
![Stars](https://img.shields.io/github/stars/Moonfin-Client/Smart-TV?style=flat-square)

- [Litefin](https://github.com/MoazSalem/litefin) - High-performance Jellyfin client for LG webOS and Samsung Tizen TVs. Designed to run well even on older hardware.
![Stars](https://img.shields.io/github/stars/MoazSalem/litefin?style=flat-square)

- [Breezyfin](https://github.com/botagas/Breezyfin) - Unofficial, performance-oriented Jellyfin client for LG webOS TVs. Offers a remote-friendly TV interface.
![Stars](https://img.shields.io/github/stars/botagas/Breezyfin?style=flat-square)

- [OcenFin](https://github.com/seluce/OcenFin) - Lightweight Jellyfin client built with Svelte for TV performance. Developed with heavy AI assistance, according to its FAQ.
![Stars](https://img.shields.io/github/stars/seluce/OcenFin?style=flat-square)

- [PlxNative](https://repo.webosbrew.org/apps/com.beb.plxnative/) - Unofficial native Plex client, not affiliated with Plex.

- [Immich](https://repo.webosbrew.org/apps/com.immich.webos/) - webOS client for the Immich photo server.

- [Immich TV](https://repo.webosbrew.org/apps/com.seeky91.immichtv/) - Alternative TV-oriented Immich client.

- [Gallery3D](https://repo.webosbrew.org/apps/me.mariotaku.gallery3d/) - Photo gallery app for webOS.

- [YouTube AdFree](https://github.com/webosbrew/youtube-webos) - YouTube TV app with ad blocking and SponsorBlock integration. Uninstall the official YouTube app before installing it.
![Stars](https://img.shields.io/github/stars/webosbrew/youtube-webos?style=flat-square)

- [youtube-webos](https://github.com/NicholasBly/youtube-webos) - Unofficial YouTube app for webOS without ads.
![Stars](https://img.shields.io/github/stars/NicholasBly/youtube-webos?style=flat-square)

- [youtube-webos-fork](https://github.com/foxi69/youtube-webos) - Another fork of unofficial YouTube app for webOS without ads.
![Stars](https://img.shields.io/github/stars/foxi69/youtube-webos?style=flat-square)

- [Twitch AdFree](https://repo.webosbrew.org/apps/twitch.adamffdev.v1/) - Twitch client for webOS TVs.

- [SmartTwitchWebOSTV](https://repo.webosbrew.org/apps/com.tbsniller.smarttwitchwebostv/) - Twitch client with a TV-focused experience.

- [Crunchyroll](https://repo.webosbrew.org/apps/com.crunchyroll.webos/) - Crunchyroll client for webOS.

- [Crunchyroll Stream](https://repo.webosbrew.org/apps/com.crunchyroll.stream.app/) - Another Crunchyroll client for webOS.

- [BiliTV](https://repo.webosbrew.org/apps/com.biliwebos.app/) - Bilibili client for webOS TVs.

- [Bili webOS](https://github.com/asdf17128/bili-webos) - Open-source Bilibili client for LG webOS TVs.
![Stars](https://img.shields.io/github/stars/asdf17128/bili-webos?style=flat-square)

- [Qoder IPTV Player](https://repo.webosbrew.org/apps/com.qoder.iptv/) - IPTV player for webOS.

- [WebOS TVHeadend Client](https://repo.webosbrew.org/apps/com.willinux.tvh.app/) - Client for watching live TV from a TVHeadend server.

- [Subsonic Player](https://repo.webosbrew.org/apps/com.subsonic.player/) - Web-based music player for Subsonic-compatible servers.

- [Sendspin Cinema](https://repo.webosbrew.org/apps/com.sendspin.cinema/) - Multimedia app available through the Homebrew Channel.

- [streamkatze](https://repo.webosbrew.org/apps/org.webosbrew.streamkatze/) - Streaming app available through the Homebrew Channel.

- [DecoTV](https://repo.webosbrew.org/apps/com.cheerchen.decotv/) - Media app available through the Homebrew Channel.

- [Nuvio Native Legacy](https://github.com/iqui27/nuvio-native-legacy) - Native media application project for webOS.
![Stars](https://img.shields.io/github/stars/iqui27/nuvio-native-legacy?style=flat-square)

- [Decoder bench](https://repo.webosbrew.org/apps/io.github.beatcracker.decoderbench/) - Tool for testing the TV's video decoding capabilities.

- [native-jelly](https://github.com/sostk/native-jelly) - A native Jellyfin client adapted from PLX Native, with a modern TV-focused interface and Jellyfin support.
![Stars](https://img.shields.io/github/stars/sostk/native-jelly?style=flat-square)

- [CSWeb TV](https://github.com/sostk/cloudstream-webos-native) - A native LG webOS TV app that runs unmodified CloudStream .cs3 extensions on the TV.
![Stars](https://img.shields.io/github/stars/sostk/cloudstream-webos-native?style=flat-square)

- [aurora-tv](https://github.com/GuiDev1994/aurora-tv) - Unofficial fork of Moonlight TV for LG webOS (C1–C5 and compatible sets), focused on high-quality streaming on OLED TVs with a remote- and gamepad-friendly UI.
![Stars](https://img.shields.io/github/stars/GuiDev1994/aurora-tv?style=flat-square)

- [StashWebOS](https://github.com/pustal/StashWebOS) - An unofficial Stash client for LG webOS TVs, made for the remote and careful with the TV's small storage.
![Stars](https://img.shields.io/github/stars/pustal/StashWebOS?style=flat-square)

- [StremCompat](https://github.com/Alexesmm/stremcompat-lg-webos) - Unofficial compatibility client for older ARMv7 LG TVs running webOS 3.x and 4.x; installs through Developer Mode without root access.
![Stars](https://img.shields.io/github/stars/Alexesmm/stremcompat-lg-webos?style=flat-square)

## Games and game streaming

- [RetroArch](https://repo.webosbrew.org/apps/com.retroarch.webos/) - Libretro emulation frontend. It may need the [webOS 64-bit bridge](https://repo.webosbrew.org/apps/org.webosbrew.bridge-64to32/), so check the current instructions for your TV.

- [Moonlight TV](https://github.com/mariotaku/moonlight-tv) - Lightweight NVIDIA GameStream client for streaming PC games to your TV. Supports up to four controllers.
![Stars](https://img.shields.io/github/stars/mariotaku/moonlight-tv?style=flat-square)

- [IHSplay](https://repo.webosbrew.org/apps/org.mariotaku.ihsplay/) - In-home game streaming client for webOS.

- [Punktfunk](https://repo.webosbrew.org/apps/io.unom.punktfunk.client-webos/) - Game-streaming client listed under games in the Homebrew catalog.

- [PocketVibe](https://github.com/tolgakurtuluss/pocketvibe-webos) - webOS port of [PocketVibe](https://github.com/cobanov/pocketvibe), a launcher and collection of Three.js games.
![Stars](https://img.shields.io/github/stars/tolgakurtuluss/pocketvibe-webos?style=flat-square)

- [OpenTTD](https://repo.webosbrew.org/apps/com.leondrolio.x.openttd/) - Open-source transport simulation game.

- [Chocolate Doom Demo](https://repo.webosbrew.org/apps/org.chocolate-doom.demo/) - Demo build of the classic Doom source port.

- [3D Pinball – Space Cadet](https://repo.webosbrew.org/apps/com.github.k4zmu2a.space-cadet-pinball/) - Port of the classic Windows pinball game.

- [2048 Port for WebOS](https://repo.webosbrew.org/apps/com.gabrielecirulli.app2048.webos/) - Port of the 2048 puzzle game.

- [Fruit Ninja](https://repo.webosbrew.org/apps/com.halfbrick.fruitninja/) - Unofficial webOS version of the arcade game.

- [gfn-webos](https://github.com/duffpl/gfn-webos) - Unofficial native GeForce NOW client for LG webOS TVs, built on OpenNOW.
![Stars](https://img.shields.io/github/stars/duffpl/gfn-webos?style=flat-square)

- [SonicWebMania](https://github.com/pustal/SonicWebMania) - Sonic Mania for LG webOS TVs. Requires the user to own the game to provide the assets.
![Stars](https://img.shields.io/github/stars/pustal/SonicWebMania?style=flat-square)

- [Animal Crossing Port for WebOS TVs](https://github.com/pustal/Animal-Crossing-WebOS) - Animal Crossing (GameCube) for LG webOS TVs. Requires the user to own the game to provide the assets.
  ![Stars](https://img.shields.io/github/stars/pustal/Animal-Crossing-WebOS?style=flat-square)

## Ambilight and lighting

- [PicCap](https://github.com/TBSniller/piccap) - Ambilight sender app that works with compatible Hyperion setups.
![Stars](https://img.shields.io/github/stars/TBSniller/piccap?style=flat-square)

- [Piccap On/Off Remote](https://repo.webosbrew.org/apps/ui30/) - Remote toggle for PicCap.

- [HyperHDR](https://repo.webosbrew.org/apps/org.webosbrew.hyperhdr.loader/) - Ambient-lighting service and frontend, intended to be used with PicCap.

- [Hyperion.NG](https://repo.webosbrew.org/apps/org.webosbrew.hyperion.ng.loader/) - Ambient-lighting service that runs on the TV and works with PicCap.

- [lg-hue-sync](https://github.com/adeze/lg-hue-sync) - Native LG webOS ambient sync for Philips Hue Entertainment and Nanoleaf 4D.
![Stars](https://img.shields.io/github/stars/adeze/lg-hue-sync?style=flat-square)


## Screensavers

- [Custom Screensaver](https://repo.webosbrew.org/apps/org.webosbrew.custom-screensaver/) - Lets you use your own screensaver on rooted TVs.

- [Aerial Screensaver](https://repo.webosbrew.org/apps/org.aabytt.webos.custom-screensaver-aerial/) - Aerial-style custom screensaver for webOS.

- [Aerial webOS screensaver](https://repo.webosbrew.org/apps/org.rchalaaa.webos.custom-screensaver/) - Another aerial-style custom screensaver.

- [Idlegif](https://repo.webosbrew.org/apps/org.oted.idlegif/) - Idle-time screensaver app listed in the Homebrew catalog.

## TV utilities

- [VPN Client](https://repo.webosbrew.org/apps/com.sk.app.lgtv-vpn/) - OpenVPN client with a control interface for webOS.

- [WireGuard VPN](https://repo.webosbrew.org/apps/com.github.cfernande1470.wireguard/) - WireGuard VPN client for webOS.

- [VNCServer](https://repo.webosbrew.org/apps/org.webosbrew.vncserver/) - VNC server for viewing and controlling the TV remotely.

- [RustCouch](https://github.com/danzig666/webos-rustdesk-client) - RustDesk-compatible remote desktop client for controlling a Windows, Linux or macOS computer from the TV with the Magic Remote, on-screen keyboard or a USB/Bluetooth keyboard. Tested on an LG C3.
![Stars](https://img.shields.io/github/stars/danzig666/webos-rustdesk-client?style=flat-square)

- [Open Service Menu](https://repo.webosbrew.org/apps/com.open.hidden.menu/) - Opens the TV's hidden service menu.

- [Sound Mode Fix](https://repo.webosbrew.org/apps/eu.depau.webos.soundmodefix/) - Fixes sound mode behavior on webOS TVs.

- [Bluetooth Disabler](https://repo.webosbrew.org/apps/pl.krzywro.webos-bluetooth-disabler/) - Utility for disabling Bluetooth on the TV.

- [AmazOff Patcher](https://repo.webosbrew.org/apps/com.amazoff.patcher/) - Patching utility available through the Homebrew Channel.

- [CCCBib](https://repo.webosbrew.org/apps/org.webosbrew.cccbib/) - Homebrew Channel app maintained under the webosbrew organization.

- [Auto Dev Token Refresh](https://repo.webosbrew.org/apps/com.pirate.refresh/) - Refreshes the Developer Mode token on the TV.

- [dts_restore_plus](https://github.com/josippapez/dts_restore_plus) - Restore DTS audio playback (and add Matroska Dolby Vision support) on rooted LG webOS TVs, where LG deliberately removed DTS decoding in firmware.
![Stars](https://img.shields.io/github/stars/josippapez/dts_restore_plus?style=flat-square)

- [oscar-cam](https://github.com/larrysweb/oscar-cam) - A free, LAN-only camera grid for rooted LG webOS TVs. No account, no cloud, no telemetry. Camera credentials stay on the TV.
![Stars](https://img.shields.io/github/stars/larrysweb/oscar-cam?style=flat-square)

## Privacy and debloating

> ⚠️ **Note:** Blocking updates, telemetry, or network traffic can break apps and TV features. See [SAFETY.md](SAFETY.md) before applying these tools.

- [LG TV Blocklist](https://github.com/furkan-bayrak/lg-tv-blocklist) - DNS blocklists for filtering LG TV telemetry, ads, and phone-home traffic, with several filtering tiers.
![Stars](https://img.shields.io/github/stars/furkan-bayrak/lg-tv-blocklist?style=flat-square)

- [LG App Update Blocker](https://repo.webosbrew.org/apps/org.webosbrew.appupdateblocker/) - Prevents LG from automatically updating installed apps.

- [Life's Good Without Spying](https://github.com/lewisdoesstuff/lifesgoodwithoutspying) - A webOS homebrew app that switches off the surveillance stack on rooted LG TVs: ad delivery, Automatic Content Recognition, and always-on voice capture.
![Stars](https://img.shields.io/github/stars/lewisdoesstuff/lifesgoodwithoutspying?style=flat-square)


## Launchers and home screens

- [Glasshouse](https://github.com/rorygallagher2024/glasshouse) - Rooted-TV dashboard with a home screen, app management, debloating, ad blocking, and custom screensavers.
![Stars](https://img.shields.io/github/stars/rorygallagher2024/glasshouse?style=flat-square)

 
- [Hearth](https://github.com/rudra-avatar/Hearth) - Customizable home screen with a clock, weather, wallpapers, and app rows. Some features need root.
![Stars](https://img.shields.io/github/stars/rudra-avatar/Hearth?style=flat-square)

 
- [OpenLauncher](https://github.com/Shantil-K/OpenLauncher) - Launcher with folders, video wallpapers, and widgets. Requires webOS 6 or newer, and some features need root.
![Stars](https://img.shields.io/github/stars/Shantil-K/OpenLauncher?style=flat-square)

- [webOS Custom Home](https://github.com/zzeppieri/webos-custom-home) - Ad-free custom home screen for rooted TVs with app and input discovery and widgets.
![Stars](https://img.shields.io/github/stars/zzeppieri/webos-custom-home?style=flat-square)

 
- [LG Luma](https://github.com/ecklf/lg-luma) - Alternative home-screen project for LG TVs.
![Stars](https://img.shields.io/github/stars/ecklf/lg-luma?style=flat-square)

 
- [Free My TV](https://github.com/simbasjungles/free-my-tv) - A fast, ad-free home screen for Google TV, LG webOS and Samsung Tizen. One button to undo.
![Stars](https://img.shields.io/github/stars/simbasjungles/free-my-tv?style=flat-square)

- [Lumen webOS fork](https://github.com/ammar027/lumen-webos) - Lumen: a tvOS-style, GPU-light home screen for rooted LG webOS TVs (patches on partridgeworks/webos-launcher)
![Stars](https://img.shields.io/github/stars/ammar027/lumen-webos?style=flat-square)

- [webos-homebar](https://github.com/rawinek/webos-homebar) - Homebar: the home screen as a bar over the picture, not a full-screen menu, for rooted LG webOS TVs.
![Stars](https://img.shields.io/github/stars/rawinek/webos-homebar?style=flat-square)

- [rivera-interface-beta](https://github.com/mexicanninja250/rivera-interface-beta) - An Apple TV-inspired Home launcher for rooted LG webOS 10 TVs, built on Glasshouse. Scenic backgrounds, app previews, weather, and a smoother entrance.
![Stars](https://img.shields.io/github/stars/mexicanninja250/rivera-interface-beta?style=flat-square)

- [CleanYourTV for LG webOS](https://github.com/lasharor/cleanyourtv-WebOS) - A home screen that replaces LG's Home on rooted LG webOS TVs; requires root and the Homebrew Channel. Reported working on webOS 5, 6 and 23 to 26
![Stars](https://img.shields.io/github/stars/lasharor/cleanyourtv-WebOS?style=flat-square)

- [WiiOS](https://github.com/KaykCaputo/WiiOS-webOS) - Wii-inspired home screen launcher for LG webOS TVs. ![Stars](https://img.shields.io/github/stars/KaykCaputo/WiiOS-webOS?style=flat-square)

- [webOS Console Home](https://github.com/testtrader1993/webos-console-home) - Console-style home screen with large tiles for HDMI inputs, settings and screen off, installed through Developer Mode without root. Tested on webOS 6.5. ![Stars](https://img.shields.io/github/stars/testtrader1993/webos-console-home?style=flat-square)

- [ATLauncher](https://github.com/ratelimits/atlauncher) - Apple TV-inspired native (QML) home screen with a Liquid Glass Dock, App Store app icons, Top Shelf splashes and TMDB popular shows, for rooted TVs with the Homebrew Channel. Tested on webOS 25 (LG UR8000). ![Stars](https://img.shields.io/github/stars/ratelimits/atlauncher?style=flat-square)

## Rooting and recovery

> ⚠️ **Caution:** Rooting methods are firmware-specific and may be patched. Verify current compatibility and recovery instructions before proceeding, and read [SAFETY.md](SAFETY.md) first.

- [Can I Root My TV?](https://cani.rootmy.tv/) - Checks whether your TV model and firmware can be rooted.

- [RootMyTV](https://github.com/RootMyTV/RootMyTV.github.io) - Rooting project for supported LG webOS TVs. Compatibility depends on model and firmware.
![Stars](https://img.shields.io/github/stars/RootMyTV/RootMyTV.github.io?style=flat-square)

- [DejaVuln Autoroot](https://github.com/throwaway96/dejavuln-autoroot) - Automates DejaVuln-based rooting and Homebrew Channel setup on supported TVs.
![Stars](https://img.shields.io/github/stars/throwaway96/dejavuln-autoroot?style=flat-square)

- [Faultmanager Autoroot](https://github.com/throwaway96/faultmanager-autoroot) - Rooting and Homebrew Channel setup tool for certain webOS 4.0 and newer TVs.
![Stars](https://img.shields.io/github/stars/throwaway96/faultmanager-autoroot?style=flat-square)
 
- [DangBro](https://github.com/azoffshowy/dangbro) - SSAP tooling for working with the webOS TV protocol.
![Stars](https://img.shields.io/github/stars/azoffshowy/dangbro?style=flat-square)
 
- [webOS Terminal](https://repo.webosbrew.org/apps/com.github.gprot42.webosterminal/) - Native terminal for rooted TVs. Requires Homebrew Channel.

- [own-your-glass](https://github.com/JulioFerrero/own-your-glass) - Harden a rooted LG webOS TV — kill the microphones, stop the screen-capture leak, block the ad/telemetry endpoints, and debloat the services you never asked for.
![Stars](https://img.shields.io/github/stars/JulioFerrero/own-your-glass?style=flat-square)


## Remote control

- [LG Input Hook](https://github.com/Simon34545/lginputhook) - Remaps remote-control buttons on supported LG webOS TVs.
![Stars](https://img.shields.io/github/stars/Simon34545/lginputhook?style=flat-square)

- [Magic Mapper for webOS](https://github.com/afonsojramos/magic-mapper-webos) - TV-native interface for [Magic Mapper](https://github.com/andrewfraley/magic_mapper) that disables, remaps, or redirects LG Magic Remote buttons without editing JSON over SSH. Requires root and the Homebrew Channel. Tested on an LG C3 running webOS 25.
![Stars](https://img.shields.io/github/stars/afonsojramos/magic-mapper-webos?style=flat-square)

 
- [LG Remote](https://github.com/heroslender/lg-remote) - Android app for controlling LG TVs over webOS network APIs.
![Stars](https://img.shields.io/github/stars/heroslender/lg-remote?style=flat-square)

 
## Community

- [Original Reddit resource discussion](https://www.reddit.com/r/webos/s/LfDWRakWmp) - The discussion that inspired this list.

- [r/webos](https://www.reddit.com/r/webos/) - Community for webOS discussions, recommendations, and troubleshooting.

- [webOS Homebrew Project: Dev Mode guide](https://www.webosbrew.org/devmode) - Community walkthrough for enabling Developer Mode.

- [webOS Homebrew Project: Rooting guide](https://www.webosbrew.org/rooting) - Community guide to rooting supported TVs.

- [LG TV GitHub Stars list](https://github.com/stars/m1804-code/lists/lg-tv) - Community-curated list of LG TV-related repositories.

- [How to Install and Set Up Ambilight on LG webOS](https://github.com/satgit62/How-to-Install-and-set-up-Ambilight-on-LG-webOS) - Setup guide for PicCap with Hyperion or HyperHDR.

- [Glasshouse network-filtering discussion](https://github.com/rorygallagher2024/glasshouse/discussions/932) - Discussion about network-level filtering on webOS TVs.

- [Guide about rooting your TV](https://tv.slada.sk/guides/rooting-guide) - Guide for rooting shared on "tv.slada.sk" website.


## Footnotes

- Compatibility, maintenance status, and root requirements can change. Check each project's documentation before installation.
- Star counts are a rough popularity signal, not a measure of quality or safety.
- Inclusion is not a security audit or an endorsement by project maintainers.
- This list is an independent community resource and is not affiliated with LG Electronics.

## Contributing

Please read [CONTRIBUTING.md](https://github.com/tolgakurtuluss/awesome-webos/blob/main/CONTRIBUTING.md) before proposing an addition. Safety and compatibility notes are in [SAFETY.md](https://github.com/tolgakurtuluss/awesome-webos/blob/main/SAFETY.md).
