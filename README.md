# The Sims 2 Legacy Collection - Ikea SP
An easy way to restore The Sims 2: IKEA Home Stuff to The Sims 2 Legacy Collection.

## How to restore

1. You need SP files from `The Sims 2 Ultimate Collection` or, for example, from a CD/DVD (in this case, follow the [The Sims 2: IKEA Home Stuff disc edition steps below](https://github.com/hiloyt/the-sims-2-legacy-ikea/main/README.md#the-sims-2-ikea-home-stuff-disc-edition)).
2. Make a copy and rename the directory with SP files from `The Sims 2 IKEA® Home Stuff` to `SP8`. In your case, it can have a slightly different name, but it should contain the `TSData` folder.

### Steam

3. Download the file `3314070_install.vdf` from this repo.
4. Move the `SP8` folder to your game location (to the main catalogue where you see similar dirs) and replace your `3314070_install.vdf` with mine.
5. Start the game, and you will see Ikea items. Have fun! :)

### EA/Epic

3. Download the file `ts2_legacy_ikea_stuff.reg` from this repo. Open it with Notepad/Notepad++ or any other text editor. Change the path `C:\\Program Files\\EA Games\\The Sims 2 Legacy\\SP8` to yours where you have the game. Remember to always use `\\` after each part of the path!
4. Move the `SP8` folder to your game location (to the main catalogue where you see similar dirs).
5. Double-click `ts2_legacy_ikea_stuff.reg` and click `Yes` at the prompt to add the keys to your Windows registry.
6. Start the game, and you will see Ikea items. Have fun! :)

## Additional information

### Missing Ikea collections
If you started the game before adding the SP8 or something strange happened, Ikea collections will be missing from the build mode. But this can be fixed easily!

1. Go to the `The Sims 2 Legacy Collection\SP8\TSData\Res\UserData\Collections` dir, where your game is.
2. Copy three files - `IKEA_Bedroom.package`, `IKEA_Living_Room.package` and `IKEA_Stuff.package`.
3. Then copy them to `Documents\EA Games\The Sims 2 Legacy\Collections`. If they are there already, you can skip this entire process.
4. Start the game, and you should see Ikea collections in the build mode.

Big thanks to [@AltEvolutions](https://github.com/hiloyt/the-sims-2-legacy-ikea/issues/1) for spotting missing collections in some cases and @thurask for the registry file :).

### The Sims 2: IKEA Home Stuff disc edition
You must make small file changes if you have a disk version of this SP.

1. Insert the disc edition to your computer or use your backup in the .iso format.
2. Create the `SP8' directory somewhere (for example, in `Downloads`) and copy the `TSData` folder and the `compressed.zip` file from the disc/ISO to it.
3. Now, you need to extract the `compressed.zip` file. After that, you should have three folders in your 'SP8' dir: `CSBin`, `TSBin` and `TSData`. You only need the `TSData` one, but you can copy all of them or remove everything excluding `TSData`.
4. You can now follow the original tutorial again, starting from `step 3` for your game type.

## Useful notes

1. The structure of the game folder should look like this:
![image](https://github.com/user-attachments/assets/7b31a32c-bd5a-4894-adbf-c4d0b626d88f)
2. The structure of the SP folder should look like this:
![image](https://github.com/user-attachments/assets/f9e36119-a08f-40c4-817d-3ad85bc4f9c0)

