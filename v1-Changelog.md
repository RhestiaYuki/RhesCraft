Link to full changelog history (or easier reading) : [Link](https://github.com/RhestiaYuki/RhesCraft/blob/master/v1-Changelog.md)

#### V1.2.2 (A)

###### *Alpha versions are untested/undergoing testing and may break worlds when updated*

- Added the Occultism dependency [ForgeBrainLib](https://www.curseforge.com/minecraft/mc-mods/forgebrainlib)
- Downgraded back Forge to 43.1.65 due to some mods causing [launch issues](https://forums.minecraftforge.net/topic/118938-forge-4320-minecraft-1192-exception-in-thread-main-javalangillegalargumentexception-10-119-empty-pre-release/)  along with some mods that had dependency on Forge 43.2.0. 

#### V1.2.1 (A)

###### *Alpha versions are untested/undergoing testing and may break worlds when updated*

- Added the Occultism dependency [ForgeBrainLib](https://www.curseforge.com/minecraft/mc-mods/forgebrainlib)
- Updated Forge to 43.2.0

#### V1.2.0 (A)

###### *Alpha versions are untested/undergoing testing and may break worlds when updated*

- Added the following mods (+ their dependencies) as they were finally ported to 1.19.2 or missed when I first made the modpack
    1. [AE2 Things](https://www.curseforge.com/minecraft/mc-mods/ae2-things-forge)
    2. [Better Advancements](https://www.curseforge.com/minecraft/mc-mods/better-advancements)
    3. [Botania](https://www.curseforge.com/minecraft/mc-mods/botania)
    4. [Comforts](https://www.curseforge.com/minecraft/mc-mods/comforts)
    5. [Cosmetic Armor](https://www.curseforge.com/minecraft/mc-mods/cosmetic-armor-reworked)
    6. [Crafting Tweaks](https://www.curseforge.com/minecraft/mc-mods/crafting-tweaks)
    7. [Dark Utilities](https://www.curseforge.com/minecraft/mc-mods/dark-utilities)
    8. [Engineer's Decor](https://www.curseforge.com/minecraft/mc-mods/engineers-decor)
    9. [Mekanism Generators](https://www.curseforge.com/minecraft/mc-mods/mekanism-generators)
    10. [OpenBlocks Elevator](https://www.curseforge.com/minecraft/mc-mods/openblocks-elevator)
    11. [Reliquary](https://www.curseforge.com/minecraft/mc-mods/reliquary-v1-3)
    12. [Rubidium](https://www.curseforge.com/minecraft/mc-mods/rubidium) - This is added with a known [crash issue](https://github.com/CaffeineMC/sodium-fabric/issues/1486) that is related to NVIDIA. As this is a client-side mod, just remove it if it causes crashing issues
    13. [Simply Light](https://www.curseforge.com/minecraft/mc-mods/simply-light)
    14. [Twilight Forest](https://www.curseforge.com/minecraft/mc-mods/the-twilight-forest)
    15. [When Dungeons Arise](https://www.curseforge.com/minecraft/mc-mods/when-dungeons-arise)
    
- Removed the following mods as they were either causing issues or redundant
    1. Bed Benefits
    2. Bottle your XP
    3. Easy Magic (doesn't work with Apotheosis installed)
    4. Everlasting Abilities (the config doesn't work so nothing can be configured and it becomes really broken)
    5. Experience Obelisk 
    6. Realistic Torches (there's just too many other torch variants)
    
 - Updated mods. There's too many to list so I'm not going to list it. Check on [GitHub](https://github.com/RhestiaYuki/RhesCraft) where I actually push my changes for tracking.
---

#### V1.1.1 (R)

- Updated Forge version to 43.1.55 as [AE2](https://www.curseforge.com/minecraft/mc-mods/applied-energistics-2) requires it.
- Removed [Debugify](https://www.curseforge.com/minecraft/mc-mods/debugify) as it was not loading properly despite ClothConfig API dependency existing. Previous version of debugify was a Fabric version which didn't trigger any errors but was not loaded in anyway.
- Started using semantic versioning number to handle smaller updates like this 

---

#### V1.1.0 (R)

- Added [Productive Bees](https://www.curseforge.com/minecraft/mc-mods/productivebees)
- Added back [Cyclic](https://www.curseforge.com/minecraft/mc-mods/cyclic) (not like this was in previous versions that was visible)

