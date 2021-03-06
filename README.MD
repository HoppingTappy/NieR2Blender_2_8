![Nier2Blender](https://user-images.githubusercontent.com/54476280/64488614-519a7280-d24a-11e9-8627-784cdc5ac3de.png)
<br>

This fork is being updated by **Woeful_Wolf** in an attempt to keep Nier2Blender alive for Blender 2.8 and the future versions <br>

<br>

Materials/textures have been redone completely due to the new Blender 2.8 rendering engines updates. <br>
This means it now has **Eevee/Cycles material import support for the Principled Shader! PBR Yay!** <br>

<br>

This is still a bit WIP so reporting any bugs would be appreciated, I could not test with every model in the game but if you find any that are problematic, be sure to include what model it was (helps with debugging). <br>
<br>
If looking for the exporter, here it is: <br>
https://github.com/WoefulWolf/Blender2NieR
<br>
(And thanks for helping with testing; Kekoulis)
<br>
<br>
If you use my tool and release something, please give appropriate credit and info. I would really love for my tools to become more 
widely known so that others can start modding too. :)

## What have I added exactly?

* Blender 2.8 Support
* Importing to Eevee/Cycles
* Alpha Channel Support
* MaskMap Support
* LightMap Support
* Multiple Normal Map Support
* Importing straight from .DTT files directly (skips manual extraction)
* (and probably some other small things I've forgotten)

<br>

![2B](https://i.imgur.com/WObGcDP.png)

## What is nier2blender?

* A Blender plugin for importing NieR:Automata's .wmb (or now .dtt) files to with official rigging.<br>

## PS:

* #### PS1: Where to find .wmb files?
    wmb files are packed in .cpk files under the game data folder which can be unpack by CriPakTools.<br>
    unpack the .cpk files and find .dat and .dtt files both of them are necessary for extracting models<br>
    unpack .dat and .dtt files using dat_unpacker.py<br>
    .wmb files can be found in unpacked .dtt files<br>


* #### PS2: Put .dat and .dtt files in pair under the same folder
    .dat and .dtt file have the same name file name are paired<br>
    .dat file contains control information such material, motions of the model <br>
    .dtt file contains .wmb model and texture package<br>

* #### PS3：Useful folders in cpk
    /pl -> main character models<br>
    /wd -> scence models<br>
    /wp -> weapon models<br>
    /um -> npc models<br>
    /em -> enemy models<br>
    /et -> item models<br>

* #### PS4: Tips
    unpack all cpk files and merge them under the same forlder before unpack dat and dtt files

*  #### PS4 Pro:
    just a joke enjoy it.
