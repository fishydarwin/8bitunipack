# 8Bit University Resource Pack

The pack used for **8Bit University**, a Minecraft: Java Edition server.

## Licensing

Because we believe Minecraft is a game that inspires creativity, we are releasing the pack on our GitHub for others to view the inner workings. Ultimately, any server resource pack can be copied over and redistributed, and hiding it behind curtains will only make people steal it.

The pack is free to be downloaded from the Releases tab, and GitHub logs will help keep track of what changed over its development.

**With all this said, though,** we request that you do not claim the pack or any of its contents as your own. Other than that, you are free to use the resource pack for any creative work of your own (videos, inspiration, whatever else...)

## Downloads

The pack can be downloaded in `.zip` format from the Releases tab.
Simply drag & drop the pack over in your `.minecraft/resourcepacks` folder.

Usually, the designated version for a resource pack is the latest version Minecraft offers, but older versions of the pack should work with newer versions of the game just fine in most cases. Despite this, we do recommend you use the pack on the correct version for the optimal experience.

## Compatibility

We test the pack for compatibility against **Vanilla Minecraft**.
This means that you shouldn't require any mods such as OptiFine for special texture handling.

The file size of the pack is also kept minimal to avoid client-side lag, and for faster download times.

## Structure

Custom content (usually models and textures) are included inside their respective folders (for example models go in `assets/minecraft/models`), except in a folder named `custom` (therefore, `assets/minecraft/models/custom`)

Each custom object is placed by this rule:
+ Custom models are simply placed directly (for example `assets/minecraft/models/custom/something.json`)
+ Everything else has a dedicated folder (for example `assets/minecraft/textures/custom/something/texture1.png`)

We explicitly avoid needless categorization as this leads to more trouble in the end.

When some content must replace Vanilla content, it is placed as it would be in the Vanilla default pack, using typical resource pack logic (for example, to replace the `dirt.png` texture, simply add a texture at `assets/minecraft/textures/dirt.png`)