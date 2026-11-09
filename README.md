# Cull Less Leaves — Explore Dense Forests Without FPS Drops

Cull Less Leaves 9minecraft Mod optimizes leaf rendering to boost frame rates around heavy tree areas. It stops the game from drawing hidden block faces inside thick foliage that players cannot see. This mod keeps forests looking full and natural while reducing lag on low-end systems. It works strictly on the client side, so you can join any server without issues. You can add or remove it from your game at any point without breaking your world saves.

## What this build is

An unofficial rebuild of **isxander**'s original work, kept running on current Minecraft releases by 9Minecraft Studios. Not affiliated with the original author and not endorsed by them.

Most of the porting work sits in the mixin layer. Each Minecraft release moves or renames the methods this mod hooks into, so the hooks are re-pointed and re-tested against that version rather than rewritten. The behaviour underneath is upstream's and is deliberately left alone — that is the part that makes the mod feel right, and it is not ours to redesign.

## Source code

This build is released under **LGPL-3.0-or-later**. The complete corresponding source ships inside the downloadable file under `META-INF/sources/`, next to the original licence text.

## Versions

| Minecraft | Loader |
|---|---|
| 26.3 | Fabric, NeoForge |
| 26.2 | Fabric, NeoForge |
| 1.21.11 | Fabric, NeoForge |

## Getting the built mod

Install steps, the dependency list, the screenshot gallery and what changed in each release are kept together on the download page:

[9minecraft.net/cull-less-leaves-9minecraft-mod](https://www.9minecraft.net/cull-less-leaves-9minecraft-mod/)

## Credits

Original work by **isxander**. Port and maintenance by 9Minecraft Studios. Licensed LGPL-3.0-or-later; the upstream licence text ships inside every build.
