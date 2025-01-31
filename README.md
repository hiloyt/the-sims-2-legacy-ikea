# The Sims 2 Legacy Collection - Ikea SP
An easy way to restore The Sims 2: IKEA Home Stuff to The Sims 2 Legacy Collection.

## How to restore

### Steam

1. You need SP files from `The Sims 2 Ultimate Collection` or, for example, from a disk.
2. Make a copy and rename the directory with SP files from `The Sims 2 IKEA® Home Stuff` to `SP8`. It can be different in your case but should contain the `TSData` folder.
3. Download the file `3314070_install.vdf` from this repo.
4. Move the `SP8` folder to your game location (to the main catalogue where you see similar dirs) and replace your `3314070_install.vdf` with mine.
5. Start the game, and you will see Ikea items. Have fun! :)

### EA/Epic

1. You need SP files from `The Sims 2 Ultimate Collection` or, for example, from a disk.
2. Make a copy and rename the directory with SP files from `The Sims 2 IKEA® Home Stuff` to `SP8`. It can be different in your case but should contain the `TSData` folder.
3. Download the file `ts2_legacy_ikea_stuff.reg` from this repo.
4. Move the `SP8` folder to your game location (to the main catalogue where you see similar dirs).
5. Double-click `ts2_legacy_ikea_stuff.reg` and click `Yes` at the prompt to add the keys to your Windows registry.
6. Start the game, and you will see Ikea items. Have fun! :)

## Missing Ikea collections
If you started the game before adding the SP8 or something strange happened, Ikea collections will be missing from the build mode. But this can be fixed easily!

1. Go to the `The Sims 2 Legacy Collection\SP8\TSData\Res\UserData\Collections` dir, where your game is.
2. Copy three files - `IKEA_Bedroom.package`, `IKEA_Living_Room.package` and `IKEA_Stuff.package`.
3. Then copy them to `Documents\EA Games\The Sims 2 Legacy\Collections`. If they are there already, you can skip this entire process.
4. Start the game, and you should see Ikea collections in the build mode.

Big thanks to [@AltEvolutions](https://github.com/hiloyt/the-sims-2-legacy-ikea/issues/1) for spotting missing collections in some cases and @thurask for the registry file :).