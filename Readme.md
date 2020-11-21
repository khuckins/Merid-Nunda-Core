# Merid-Nunda Core
> The Colored Rooms are a rotating Wheel, a mournful imitation of Nirn, which Meridia so longs to be a true part of. Her wheel has no temperance, though; it is impatient and whirls this way and that, changing faster than a mortal can compregened, if indeed it has ever changed at all.

 Merid-Nunda Core is the library behind Adventurer's Guide to Tamriel. It contains scripts, spells, statuses, passives, and various other supplemental material that Adventurer's Guide to Tamriel may draw on. Used by itself, you will see no changes - however, it is a requirement for any mod that draws on its content. Consider it a modder's resource.

#### Why Merid-Nunda?
Merid-Nunda is the original name for Meridia, a Daedric Prince who was originally an et'Ada, a being that fled to Aetherius when the mortal realm was created. The et'Ada's flight broke holes into the universe, through which Magicka was able to flow.


## Installation
This mod works with Candor Mod Manager, Vortex Mod Manager, and Manual Installations. Candor is by far the simplest method, and as such is the recommended one.

![Compatible with Vortex Mod Manager](https://i.imgur.com/loTUWPA.png) ![Compatible with Vortex Mod Manager](https://i.imgur.com/UXk5kuH.png)
### Candor
1. Select Baldur's Gate 3 in Candor Mod Manager
2. Select "Add Mods" and choose the .zip file containing this mod
3. Check "Merid-Nunda" and hit "Install Selected Mods"

### Manual
1. Place the included .pak file into \Documents\Larian Studios\Baldur's Gate 3\Mods\
2. Edit \Documents\Larian Studios\Baldur's Gate 3\PlayerProfiles\[Profile Name]\modsettings.lsx:
3. Place this under the ModOrder children node: (This step is technically unnecessary)
```
            <node id="Module">
              <attribute id="UUID" type="FixedString" value="46c59a34-b3b1-40d0-8424-6f59ded3d575"/>
            </node>
```
4. Place this under the Mods Children Node, beneath the Gustav ModuleShortDesc block:
```
            <node id="ModuleShortDesc">
              <attribute id="Folder" type="LSWString" value="Merid-Nunda"/>
              <attribute id="MD5" type="LSString" value=""/>
              <attribute id="Name" type="FixedString" value="Merid-Nunda"/>
              <attribute id="UUID" type="FixedString" value="b59526e8-cc4b-4889-916a-3910138a1b5f"/>
              <attribute id="Version" type="int32" value="1"/>
            </node>
```

## Other Links
- [GMBinder link](https://www.gmbinder.com/share/-L3u-2oe4GFo8GtXlRHC) to Adventurer's Guide to Tamriel
- [ImprovedUI](https://www.nexusmods.com/baldursgate3/mods/13) makes this mod less of a strain on the Character Creation UI
- [Candor Mod Manager](https://www.nexusmods.com/baldursgate3/mods/22) eases the process of installing mods

## Acknowledgements
- Larion Software, for working on Baldur's Gate 3 and bringing 5th Edition to PC
- Bethesda Softworks, for creating a Sci-fi/Fantasy universe that has eaten over a decade of my life
- The Baldur's Gate 3 Modding Community
- [https://github.com/ShinyHobo](ShinyHobo) for their work easing the process of creating .pak files
