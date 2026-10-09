# AltBelts for WWE 2K26

AltBelts gives some of the champions of a title a different belt. The NXT Tag Team
Championship '13-'17, for example, comes with two belts, one for each partner.

It also turns a tag title into a trios title. In 3v3 Exhibition matches all three
champions defend it, and the third one is saved like the other two. The third champion
also gets the belt in the team entrance and on the arena pedestal, and the trio
celebrates its title win together.

And champions celebrate wearing their belts: when a trio or a stable wins, every
champion has their belt on the waist in the victory scene.

## Download

Get **AltBelts-Config.exe** from the [latest release](../../releases/latest).
That's all you need: the plugin travels inside the app.

## Install

1. You need a plugin loader that loads `plugins\*.dlp` and `mods\*.cak` from the game
   folder (CakeHook does both).
2. Run **AltBelts-Config.exe**. It finds the game through Steam.
3. Click **Install plugin**. The app copies the plugin into the game's `plugins`
   folder, the victory scenes into its `mods` folder, and creates the default settings.

## Set it up

Everything is done in the app, and your changes apply the next time you start the
game.

- **Pairs**: pick a championship, its alt belt and who gets the alt one: the second
  champion, women, men or everyone. On a trios title, "2nd champion" can also give the
  third champion a belt of their own, so each champion has a different one
  (experimental).
- **Trios**: pick the tag titles that are held by three.
- **Your belts**: belts added by mods show up by number. Give them a name so you can
  find them in the lists.
- **Wrong belt for someone?** AltBelts reads each wrestler's gender from the game,
  including created and modded wrestlers. If someone still gets the wrong belt, force
  women or men by wrestler ID.

## Updates

When the app starts it checks this page for a newer version. If there is one, it
shows what's new and an **Update now** button: the app downloads the new version,
checks it, replaces itself and installs the new plugin and victory scenes. Close the
game first.

## Notes

- The alt belt has to be installed in the game.
- Menus still show the main belt.
- When the game gets updated, AltBelts stops working until a new version comes out.
  The app tells you when your game version isn't supported yet.
- Trios titles work in 3v3 Exhibition. In Universe they keep two champions.
- If you used TriosDefense on its own: it's built into AltBelts now. Installing the plugin
  moves the separate one to `plugins\AltBelts backups`, and the third champions it saved
  are kept.
- AltBelts is in beta. If something goes wrong, turn on **Write a log file** in the
  app, play until it happens and share `plugins\AltBelts.log`.

## Credits

- Trios title defense: **Ripzz / PWM** (TriosDefense), built into AltBelts with their
  permission.
