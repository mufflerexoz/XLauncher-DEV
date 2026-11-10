# XLauncher

A full-screen Android home launcher and gaming frontend with a console-dashboard style:
dark backdrop, a centered top navigation bar, square "Jump back in" tiles and wide
banner cards with a bright accent focus outline. Works with touch, D-pad/TV remotes and game controllers.

## Features (v6.0.0)

- **Full screen launcher**: registers as a Home app (phones, tablets, handhelds and Android TV), keeps the system bars hidden.
- **Wallpapers**: built-in default background, your own picture, or the device wallpaper
  (including **live wallpapers**). Adjustable dimming.
- **Profile**: first-run setup with username and avatar (6 built-in avatars or a gallery picture).
  Select the avatar (top left) to open Settings.
- **Top bar**: Home, Library and Store (opens Google Play) in the center. The selected page is bright white, the others faded.
- **Jump back in**: recently opened games/apps as square tiles. *Fit to screen* (fills the width) or a fixed 6–30 tiles.
- **Banner Home**: create as many titled banner rows as you like (like folders). Pin apps to them from
  Options → *Pin to Banner Home*. Empty rows show a placeholder. Can be turned off (Home then doesn't scroll).
- **Customize** any app: tile image, icon, name, banner image and banner name. Tile and banner follow
  each other until you set both; names work the same way.
- **Launch page**: selecting a tile opens a full-screen page with the banner as background, the tile art,
  title, played status, play time and last played (play time needs Usage access). A plays, B goes back.
- **Library**: every installed app with All / Games / Apps filters and search. Hide apps from Options (Premium);
  open or unhide them from Settings → Home → *Hidden apps*.
- **Android TV**: the top bar shows the network (Wi-Fi strength / Ethernet) instead of the battery.
- **Banner sorting**: each Banner Home row can be Manual, A–Z, Z–A or Recently played.

## Free vs Premium

Premium is a one-time Google Play in-app purchase (product id `xlauncher_premium`; create it in the
Play Console as a one-time product). Without Premium you get one Banner Home row with up to 3 banners and can
change the wallpaper and username; customization (tiles, icons, banners, names), avatars, accent colors and
hidden apps are locked.
Debug builds have *Settings → Premium → Simulate Premium* for testing. Purchases only work when the app
is installed from Google Play (e.g. internal testing) and signed with your release key.

## Controls

| Input | Action |
|---|---|
| D-pad / stick | Move focus (Down from the top bar goes straight to the tiles, Up from the first row goes back to the top bar) |
| A / Enter / tap | Open launch page / select |
| A on launch page | Play |
| X / Menu / long-press | Options (pin to Banner Home, customize, app info, uninstall…) |
| Y | Pin to Banner Home |
| LB / RB | Switch Home and Library |
| B / Back | Back |

Developer: **mufflerexoz**

## Releasing to Google Play
Targets Android 16 (API 36) with Google Play Billing Library 8, as required by Play in 2026.

## Build
Requires JDK 17 and the Android SDK (API 35).
