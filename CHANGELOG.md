# Changelog

## v0.8

* Reworks local split-screen death and respawn handling to follow the original single-player behavior more closely, fixing repeated instant deaths, dead-player state mixups, and player-vs-player stomp/squish issues in 3 and 4 player sessions.
* Improves 3 and 4 player pause behavior, including player 1 pause priority, extra-player simplified menus, multi-menu handling, and short input suppression when opening the main pause menu.
* Improves input assignment and persistence so disconnected or unassigned controllers/keyboards no longer overwrite configured player inputs automatically.
* Improves startup/menu input handling, including intro skipping, mouse cursor visibility, accidental click/fire suppression, and Escape-to-quit from the main menu.
* Restores more Duke Nukem 64 presentation in split-screen, including startup animations, babes, level menu navigation, and saved level progress details.
* Adds more 2, 3, and 4 player HUD/weapon/menu tuning, including quarter-screen inventory, access card, weapon, kick, and level-result layout fixes.
* Note: 3 and 4 player split-screen modes are still experimental and need more optimization; that work is planned for upcoming versions.

## v0.7

* Improves 4 player quarter-screen HUD consistency, including health, armor, ammo, access cards, inventory item icons, item text, and square-aspect protection.
* Improves 4 player weapon presentation, including per-weapon quarter-screen offsets, muzzle flashes, tripmine hands, missile launcher parts, and weapon wheel icon scaling/centering.
* Improves 2 player HUD and weapon tuning for inventory item icons, ammo icons, missile launcher pieces, tripmine placement, and several weapon flashes.
* Improves player setup and input persistence, including default names `Player 1` through `Player 4` and saved player input assignments.
* Fixes player input disconnect/rejoin behavior so disconnecting a player no longer clears its configured input, and automatic assignment no longer duplicates keyboard/mouse unless configured manually.
* Reorganizes Control Setup with a Mouse / Keyboard submenu and fixes mouse reset defaults so camera movement sensitivity is restored correctly.
* Improves quarter-screen kick and idle animation placement, and allows weapon switching while quick kicking.
* Fixes split-screen quote/obituary placement in quarter viewports and keeps normal top notifications centered where appropriate.
* Note: 3 and 4 player split-screen modes are still experimental and need more optimization; that work is planned for upcoming versions.

## v0.6

* Improves 3 and 4 player split-screen presentation, especially quarter-screen HUD alignment, text spacing, weapon placement, flashes, and top notifications.
* Adds separate HUD and weapon debug presets for wide 1/2 and small 1/4 viewports, while keeping debug panels disabled in Release builds.
* Improves player input setup for players 3 and 4 and adds clearer disconnect handling for multiple joined players.
* Fixes and tunes Duke Nukem 64 HUD details including inventory item display, access cards, simplified pause menu styling, and debug overlay readability.
* Fixes additional local co-op gameplay issues around final exit button activation, access card transfer on disconnect/rejoin, respawn safety, look limits, and sleep/pause sound buildup.
* Note: 3 and 4 player split-screen modes are still experimental and need more optimization; that work is planned for upcoming versions.

## v0.5

* Adds the in-game Levels menu with level thumbnails, per-save progress, best times, and secret tracking.
* Improves split-screen save/load metadata and save previews.
* Improves Duke Nukem 64 split-screen pause and simplified extra-player menu behavior.
* Improves split-screen notifications, obituaries, camera effects, palette effects, access card HUD icons, and level-end results.
* Fixes several local co-op issues around new game flow, player join/disconnect, pickup/audio routing, weapon switching, final exit buttons, and player-specific input.
* Removes HUD/weapon debug tuning panels from Release builds.
* Note: 3 and 4 player split-screen modes are still experimental and need more optimization; that work is planned for upcoming versions.

## v0.4

* Improves split-screen save/load flow, including clearer prompts, larger save entries, refreshed save lists, and split-screen screenshots.
* Improves Duke Nukem 64 split-screen HUD details, including access card icons, ammo/armor/health placement, and end-level player comparison stats.
* Improves split-screen weapon positioning and effects for multiple Duke Nukem 64 weapons, including kick, muzzle flash, alien glow, tripmine, and missile launcher tuning.
* Fixes several local co-op gameplay issues, including player-specific pickup/audio behavior, jetpack/charge sounds, spawn overlap handling, player camera shake routing, and final exit button activation tolerance.
* Improves input behavior for inventory, jetpack, quick kick, save/load prompts, gamepad assignment, and local player restoration when loading saves.
* Improves updater behavior and removes menu options that are not useful for this split-screen build.
* Note: 3 and 4 player split-screen modes are still experimental and need more optimization; that work is planned for upcoming versions.

## v0.3

* Improves split-screen weapon/HUD tuning, including per-weapon offsets and scale controls.
* Fixes death/respawn stability issues in local split-screen.
* Improves pickup and player-specific audio handling.
* Adds more debug controls for Duke Nukem 64 weapon sprites and effects.
* Fixes several split-screen gameplay, rendering, updater, and input issues.

## v0.2

* Improves split-screen input, pause, and extra-player menu behavior.
* Improves split-screen HUD, weapon placement, and notification rendering.
* Improves pickup, jetpack, and local player sound handling.
* Fixes several window, weapon switching, and gameplay stability issues.

## v0.1

* Initial experimental Rednukem Split-Screen release.
* Adds local split-screen co-op support for Duke Nukem 64.
* Adds basic player input assignment and extra-player in-game setup menus.
* Adds split-screen HUD, weapon, audio, and input work in progress.
* Adds in-game update checking from GitHub releases.
