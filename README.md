# AltBelts for WWE 2K26

AltBelts gives some of the champions of a title a different belt. The NXT Tag Team
Championship '13-'17, for example, comes with two belts, one for each partner. The alt
belt shows up in entrances, in the ring before the match, in victories, on the arena
pedestal and hanging over the ring in tag ladder matches (experimental).

It also turns a tag title into a trios title. In 3v3 matches, in Exhibition and Universe,
all three champions defend it. The third champion also gets the belt in the team
entrance and on the arena pedestal, and the trio celebrates its title win together.
Exhibition saves the third champion like the other two; Universe keeps two and the third
one comes from the trio. The menus show all three: Championships in Exhibition, and Edit
Show, Edit Championships and the title picker of a match in Universe.

Mixed Tag matches can be for a title too, like normal tag matches, in Exhibition and
Universe.

And champions celebrate wearing their belts: when a trio or a stable wins, every
champion has their belt on the waist in the victory scene.

## Download

Get **AltBelts.exe** from the [latest release](../../releases/latest).
That's all you need: the plugin and its game files travel inside the app. (If you have
the older **AltBelts Config**, it updates itself to this one.)

## Install

1. You need a plugin loader that loads `plugins\*.dlp` and `mods\*.cak` from the game
   folder (CakeHook does both).
2. Run **AltBelts.exe**. It finds the game through Steam.
3. Click **Install plugin**. The app copies the plugin into the game's `plugins`
   folder, its game files (the victory scenes and the menus) into its
   `mods` folder, and creates the default settings.

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
checks it, replaces itself and installs the new plugin and its game files. Close the
game first.

## Notes

- The alt belt has to be installed in the game.
- Menus still show the main belt.
- When the game gets updated, AltBelts stops working until a new version comes out.
  The app tells you when your game version isn't supported yet.
- Trios titles and Mixed Tag title matches work in Exhibition and Universe. The
  Contenders screen in Universe still shows two champions.
- AltBelts doesn't change the game's code: everything it does goes through the game's
  data, so it stays away from the game's protection.
- If you used TriosDefense on its own: it's built into AltBelts now. Installing the plugin
  moves the separate one to `plugins\AltBelts backups`, and the third champions it saved
  are kept. The same goes for the separate TriosMenu plugin.
- All the game files now come in one `mods\AltBelts.cak`. Installing moves the older
  ones (`AltBelts_ANIMS.cak`, `TRIOS_UI_TEST.cak`) to `plugins\AltBelts backups`.
- AltBelts is in beta. If something goes wrong, turn on **Write a log file** in the
  app, play until it happens and share `plugins\AltBelts.log`.

## Credits

- Trios title defense: **Ripzz / PWM** (TriosDefense), built into AltBelts with their
  permission.
