# Songs of Syx Modding Toolkit

**Alpha v1.1**

A desktop app for making Songs of Syx mods. It reads the game you have installed and writes only to your local mods folder, never to the game itself or the Steam Workshop.

Start it with `Syx Toolkit.exe`. The first run asks for your Songs of Syx folder.

## What you can do

- Create a local mod, or open one you already have, and browse its files.
- Create and edit animals, races, resources, crops, farms, minable resources, mines, refiners, workshops and pastures. The form uses the game's own tags, shows each default, and checks the values before saving. Tag descriptions come from the Songs of Syx Modding Handbook.
- See the other asset types, and why each one can't be created yet.
- Edit the mod's info.
- Check the text files the game parses for syntax errors: the files under `assets/init`, `assets/text` and `assets/audio/config`, and `_Info.txt`.
- Convert a mod's WAV, MP3, AIFF or AU files to Ogg. The original is moved out of the mod.
- Compare two game versions and see what the update means for a mod's compiled jar, then save that as a report.
- Connect your own AI agent, optionally read-only, so it can do the same work. The toolkit holds no keys and calls no AI service.
- Switch between dark and light.

A check can miss a problem, and a clean result doesn't prove the mod works in the game. Only running it does.
