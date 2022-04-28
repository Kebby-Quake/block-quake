## Block Quake
A total conversion mod for Quake featuring familiar plastic blocks.

*This is the "Vanilla Pak" version 1.0!  It's designed to replace models and monsters from Quake and can be combined with most Vanilla styled mods.  There are still some features I'd like to add like sound effects and a custom hud, but those will be developed in the future!  -Kebby_:gear:*

For more news and updates, check out the Blocky-Discord: https://discord.gg/McUS8WnrvE

---

### Installation with Source Ports:
1. Click the green **Code** button in the upper right corner of GitHub, then click **Download ZIP**.
2. Extract the new pak files and put them into your main **Id1** folder.
3. You should now have four pak files in your **Id1** folder: Quake's `pak0, pak1` and Block-Quake's `pak2, pak3`.

### Installation for Quake Remastered:
1. Rename the Block-Quake `pak3` to the name `pak1`
2. Put both the `pak1, pak2` into your Quake / rerelease / **Id1** folder.
3. Turn off the enhanced models in the Remaster's display settings.

For the Quake Remaster: 
1. Rename the Block-Quake pak3 to be called "pak1"
2. Put this "pak1" into your Quake / rerelease / **Id1** folder. 
3. Turn off the enhanced models in the Remaster's display settings.

### Uninstall:
To disable or uninstall the mod, move or delete only the Block-Quake `pak` files from your **Id1** folder.  If you are unsure which pak files belong to Block-Quake, double check the pak contents by opening it with a program like PakScape.  There will be a folder in the main directory with the title of the Block-Quake mod version.

---

### Mods and Maps:

If you combine paks from another mod that already changes the regular Quake assets like Alkaline or Arcane Dimensions you won't see anything Blocky...  When combining others mod, stick to something that mostly changes gameplay like Copper or play levels from a Map-Jam.

To play the blocky enemy test room, open the console and type `map blocky_devroom_vanilla_v4` then press enter. To get back to Quake's campaign, open the console and enter `map start`.

---

Confirmed engine compatibility:
- QuakeSpasm 0.93.2
- QuakeSpasm-Spiked
- DarkPlaces
- Remaster's KEX engine.

---

Planned Block Quake versions include:
- `Vanilla`  (FINISHED!)  A blocky-themed replacement for the regular asssets in Quake, should work with most Vanilla mods.

- `CustomC` A blocky-themed total overhaul of Quake's source code to allow more Blocky special effects and minor gameplay changes.

- `ProgsDump`  Same changes as CustomC, with the added compatibility for ProgsDump mods and Trenchbroom level editing tools.

- `Friendly`  A stand-alone version of the blocky-theme that aims to reduce Quake's **Mature** rating into an **Everyone 10+** for younger audiences to enjoy.[^2]

---

Completed Blocky stuff:
- Blocky themed characters, enemies and boss models, textures and animations.
- Blocky themed weapon pickups, weapon model textures and animations.
- Blocky themed ammo, armor, items, projectiles, props and powerup models (+BSP models).
- Blocky themed test map (blocky_devroom_vanilla_v4).

---

Planned future features:
- Add some blocky themed sound effects for weapons, enemies and objects.
- Create new custom blocky themed hud and gui graphics.
- Possible mod support for online multiplayer modes like QuakeWorld CTF *(maybe!)*
- Finish the new gibbed-limbs and blocky blood models for the CustomC source code overhaul version.
- Once CustomC is complete, implement the new source code changes into the ProgsDump version.
- Censor the entire game and remove any mature themed content and replace it with age appropriate material.
- Finish the Blocky WAD textures by adding more brick pattern variety and color options.
- Create some Blocky themed maps in Trenchbroom and maybe have a Block Quake Map Jam! *(eventually)*

---

*This whole project started in November 2021 as a joke on the Quake Mapping Discord and has since spiraled into a fully fledged total conversion!*
*Thank you to everyone in the modding and mapping community who has shared support for this silly passion project!*

[^2]: Requires custom source code and will not be compatible with the other three Block Quake versions. Censorship of mature themes in Quake can only be applied to content that has been made specfically for this version. This includes core gameplay, enemies, weapons, maps, textures and sounds. If you add different model replacements from other mods, play online, or play on regular Quake maps, there is no way to obscure content that may not be suitible for younger audiences. This version is intended for parents who wish to play Quake together with their kids. It's also a great learning oppertunity for getting into level design with Trenchbroom. Remember to be responsible and always use adult supervision!
