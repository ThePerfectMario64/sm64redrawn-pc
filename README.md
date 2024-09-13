# sm64redrawn

![Screenshot](screenshot.png)



## This is a collection of textures that have been redrawn for the Super Mario 64 port.



### OG Pack Contributors

**Aghanim, cazsu, connie, CyberCat, Devector, garrit[jkl], granvillimus, JAGSTAX, Map, Marshivolt, Mazeo, Natalie, Ray, Recompiler, roovahlees, Specialfred453, Teaufou, The Chain Smoker, TheExpectedKnight**

### Silly Coop Support

**ThePerfectMario64**

This is the result of many hours of manual work drawing these textures at 10x scale or higher.

Remember to give credit to this pack if you plan to use it in a video or other form of social media, you can also link to it here. Thank you :)

Do not redistribute this pack without explicit permission. (dw, I'm not redistributing it, Just adding some features :) )

If you're interested and would like to help out, check out our Discord server! -> https://discord.gg/7bcNTPK



### Installation

If you need help compiling the source I've added the insructions below.

<b>(Release ZIP)</b>
Extract the zip file and copy it's contents into the `res` directory inside your `build` directory.

If asked to write into subdirectories and overwrite files hit yes. This way you'll get all the textures that have been redrawn, while leaving the originals that haven't been redrawn yet intact.

NOTE:
If you're using the latest nightly version you'll need to have a `gfx` directory inside of your `res` directory. The actors, levels, and textures folders go in the `gfx` directory. It should look like this:


<pre>sm64ex
   ┗ build
       ┗ us_pc
           ┗ res
              ┗ gfx
                 ┣ actors
                 ┣ levels
                 ┗ textures</pre>

To Get This For sm64coopdx
      Download The (Repo)[https://github.com/ThePerfectMario64/sm64redrawn-pc/archive/refs/heads/master.zip]
      Unzip The Folder
      Go Into gfx
      Copy All The Folders
      Go To Your sm64coopdx Folder
      Go Into dynos
      Then Packs
      Make A Folder (The name can be really anything, I perfer SM64 Redrawn.)
      Paste The Files You Copied Into Said Folder
      Profit.

<b>(Master Clone)</b>
If you git clone the master you can just copy the `gfx` folder into your `res` directory and that's it.

### sm64nx pak file

https://drive.google.com/drive/folders/1E-iKcAie5adAF-RsXOjTSvWJku_n6SZn?usp=sharing

### sm64ex Source Compilation

This is a basic reference. It doesn't list the dependicies you'll need or specific methods you may need to use depending on your OS. If you need more information you should look at the readme here -> https://github.com/sm64pc/sm64ex/tree/nightly

If you've got your dependicies and everything is setup you should be able to just run these two commands. I tested this in Arch Linux but YMMV.

`git clone -b nightly https://github.com/sm64pc/sm64ex.git`

`make NODRAWINGDISTANCE=1 TEXTURE_FIX=1 EXTERNAL_DATA=1`

Add the flag `BETTERCAMERA=1` when building if you want to use the analog stick to directly control the camera.

### Super Mario 64 Port Source Compilation

Support coming soon...
