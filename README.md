# Gacha TCG Launcher

A game launcher for the AYN Thor. Your ROMs are cards. You don't pick what to play, you pull it.

![Tearing open a booster pack](public/pack.gif)

**[Download the latest APK](https://github.com/adthing/gacha-tcg-launcher/releases/latest)**

Open packs, put your favorites on a shelf of three, and spend golden coins on more room. Everything runs on your own library; nothing is downloaded and nothing costs real money (for now).

## Features

- **Booster packs.** One pack per system, plus a Mystery Mix. Tear one open, discover 5 random games, and swipe the keepers onto your shelf! The rest are discarded.
- **Game shelf.** Starts with 3 slots. Tap a game to launch it in its emulator.
- **Slot machine.** Go to the casino and win big! Land on a game and it launches. You can also win coins, free spins, tickets, coin boosts, mystery boxes or an extra shelf slot!
- **Shell game.** Discarded games come back in sets of five. Pick a set, watch the shuffle, pick a card, and maybe take it home!
- **Economy.** Golden coins trickle in while you're away (up to 8 hours' worth). Spend them on packs, spins, shell games and shelf slots. There's a shop.
- **Missions and levels.** Daily missions, free tickets, XP and level-up rewards.
- **Skins and cosmetics.** The themes you install for Cocoon becomes skins and cosmetics for the launcher and card packs.
- **Gamepad or touch.** D-pad, A, B, L1 and R1 work everywhere.

## Requirements

- An **AYN Thor** (Android 13, dual screen).
- [**Cocoon**](https://github.com/inssekt/CocoonFE) installed and run at least once, with your collection scraped. Gacha TCG Launcher reads its box art from `/sdcard/cocoon/downloaded_media/<system>/icon` (and `hero` for the shelf). It doesn't scrape anything itself, and games without art can't be pulled.
- **Emulators installed**, none are bundled.
- ROMs in `/sdcard/ROMS`, in the usual folders following the [ES-DE convention](https://gitlab.com/es-de/emulationstation-de/-/blob/master/USERGUIDE.md): `snes`, `n64`, `SMD`, `psx`, `psp`, `ps2`, `GameCube`, etc.

## Install

[![Add Gacha TCG Launcher to Obtainium](https://github.com/ImranR98/Obtainium/raw/main/assets/graphics/badge_obtainium.png?raw=true)](https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22dev.adrien.gacha%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2Fadthing%2Fgacha-tcg-launcher%22%2C%22author%22%3A%22adthing%22%2C%22name%22%3A%22Gacha%20TCG%20Launcher%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Atrue%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22autoApkFilterByArch%5C%22%3Atrue%7D%22%7D)

1. Download the latest APK from the [releases page](https://github.com/adthing/gacha-tcg-launcher/releases/latest) and install it, or add the repo to [Obtainium](https://github.com/ImranR98/Obtainium) with the badge above to get updates automatically.
2. Open it and grant **All files access** when asked.
3. If your ROMs or Cocoon media live elsewhere, set the folders in **Settings** and rescan.

Optional: pick a pack theme in Settings to use Cocoon's theme art on the packs.

## Disclaimer

This is a parody project. I do not condone gambling, gacha, free-to-play, freemium, or any other FOMO based game mechanic. This project comes as is with no warranty. If you have a bug or want to request a feature, you may open a Github issue but I do not make any promises of updates. It works on my machine.

## Thank you

To everyone who helped me put this together. To u/RevolutionaryCry5206 for alpha testing and feedback. And to everyone who got a chuckle (or more) out of this.
