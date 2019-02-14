<h1><p align="center">
<b>TK17 Comprehensive Guide</b></p></h1>

![TKTitle](https://raw.githubusercontent.com/tepiai/tk17/master/tk1.png)

<h2><p align="center">Acknowledgements and Intro</p></h2>
Original Credit for this guide to (http://pastebin.com/GkhhjXwp)   

Thanks to GiveHerTheD, Hootie, Caligula, and several Anons for their information.   
Thanks to the authors of the repacks, regular posters on /tk17/, and nubs for keeping the community alive.  

If you want to download, go straight to Section 3.

<p align="center">The guide is separated into several sections:</p>

> [Section 1: Glossary](#z)  
> [Section 2: Computer Requirements](#a)  
> [Section 3: Install Instructions and Download](#b)  
> [Section 4: Ingame Help (Q/A about content)](#c)  
> [Section 5: Technical Help (Q/A about files and common issues)](#d)  
> [Section 6: Useful Info](#e)  

---
Ya boi forgot markdown language over the hiatus. Great. Expect me to update this soon but not now.

For new and old anons, please post screens, models, webms, etc, in the thread, and maybe in modsgarden.cc, or even in the booru. /tk17/ is pretty accepting when it comes to that. It helps keep the community alive, which means more content for all. So, please.

If your answer is not found here, seek it out on modsgarden.cc or ask it in the thread.

In order to have a fully functioning TK17 install, you must **CAREFULLY READ** this guide.

Also, here's a reminder to **SCROLL DOWN**. There is alot of useful info in this pastebin.

Reminder to all anons that sharing models is a privilege, not a right.

---

<h2><p align="center">Useful Links:</p></h2>

Booru (Abandon hope all ye who enter here): http://klubooru.booru.org/   
Modsgarden: http://modsgarden.cc   
Legacy Pastebin (tpi/tepiai): https://pastebin.com/9KyCLnqX   
Legacy(er) Pastebin (GiveHerTheD): http://pastebin.com/PfVEFQ23   
Legacy(est) Pastebin (CaptainNegative): http://pastebin.com/GkhhjXwp

---
<h2><p align="center"><a name="z">Glossary of TK Terms:</a></p></h2>

- TheKlub17

TK17 is a fork of an old sex sim. For legal reasons, we can't name it. It is much improved in terms of content and customizability compared to its former base, and is completely free.

- Hook/Reshade/SweetFX

These "plugins" inject shader parameters into the Direct3D API to modify the "look" of games. This is what users of TK17 use to make their games look good. In honor of the brainlet anon who posted on Valentine's Day-eve, I wrote a small section on how to make TK17 look good.

- Modsgarden

This website is the central hub of TK17. As stated in this guide, it is highly recommended to register here.

- VX/R9X/7.5

These denote the version number of the TK17 application. 7.5 is the base TK17 game version. VX is an experimental update that adds new features, along with backports of features from the "original" game. R9X is a version of VX modified to be more mod-friendly.
**HOWEVER, keep in mind that VX/R9X are not recommended for first-time users, because full backwards compatibility has not been reached yet.**

- namefags on the threads

These guys are also on MG, go buy them a beer or something. Most of them have contributed well to the community.

---

<h2><p align="center"><a name="a">Computer Requirements</a></p></h2>
Vanilla TK17 can run at 60fps on 2010-era Intel iGPUs, as a reference.  
 
The spec requirements are laid out below for each Hook:
 
- Hook 3 (at 1080p):  
Dual Core CPU  
4GB of RAM  
2GB Install Space  
1GB Video Adapter (iGPU) (Anything newer than Intel GMA)  
 
- Hook 4 (at 1080p):  
Intel Dual Core/Quad Core CPU  
4GB of RAM  
3+ GB Install Space  
1GB DX10 Video Adapter (HD5850 or GTX 460se Equivalent) (GTX 660 or HD 7870 for 60FPS)  
 
- Hook 5 (at 1080p):  
Quad Core CPU  
4GB of RAM  
3+ GB Install Space  
1+ GB DX11 Video Adapter (HD5850 or GTX 460se Minimum) (HD6950 or 560ti Equivalent) (GTX 660ti or R9 280x for 60FPS)  

<p align="center">Hook5 Note</p>
Your card should support feature-level DX11. (AMD HD5000 Evergreen series or above, GTX400 Fermi or above, Intel HD Ivy Bridge or above)

The minimum specs denote GPUs which support DX11 and can technically run Hook5, but may be unplayable (as in the case of Ivy Bridge iGPUs).

If you're not a Windows 10 user (it's installed already), you should have installed the latest DirectX package.
Here: (https://www.microsoft.com/en-us/download/details.aspx?id=35)
Also install the msvc2012x86 redistributable.
Additionally, any graphic modification .dlls (earlier hook, reshade, enb) in Binaries should be deleted prior to installing hook5. Backup prior settings as needed.
 
---
<h2><p align="center"><a name="b">Install Instructions</a></p></h2>
 
Before continuing, let me make it clear that having an account on modsgarden.cc is a *REQUIREMENT*.  Yes, you can play the game without it, but you won't have access to all the mods and content that really sets this game apart from others.  If you have a problem with that, just shut up and register anyway, you'll thank me afterwards.
 
Another caveat is that some of the repacks have long loading times. Repacks like NCProductions are fast because they are barebones. Some repacks, such as LordHunt's repack, are 1-2 minutes to load but other repacks such as Matterman's or VerySlow's repacks have loading times ranging from 5-10 minutes. It is best to download a repack and then strip the vanilla files for compressed files, such as dimisd's compressed .txxs, in order to have the best of both worlds.

You do not have to install the game if you download a repack, as the reapcks are modded versions of the game packed in .zips.

Refer to the game directory description further down if you are touching repack/game files after install.
 
***A1***: Get version 7.5 or the repacks:  
(magnet:?xt=urn:btih:2589440A4E4689AF159A742CD256ED3535EEBCEE&tr=udp%3A%2F%2Ftracker.openbittorrent.com%3A80%2Fannounce&)
 
Mediafire link:  
(https://www.mediafire.com/file/f6bc4ygw6yxy2xs/TK17+Base+Game.rar)

OR GET THE REPACKS

As for ease of use, all of the repacks are the "same" difficulty.

- Slim Edition II (Hook5, fast to load. Has 4x and QoL improvements. Preinstalled content. Typical H5 w/o Reshade performace.):  
(https://mega.nz/#F!MuAXVCwI!K9MHCsrIGmVskfLrR_W5yA)  
(https://mediafire.com/folder/o88l74tjo8kbj/)  
(https://zippyshare.com/whatever321/ymekb8sx/dir.html)  

	- Slim Edition II Old Links
	(https://mega.nz/#!UmAETaYL!RUjFGszsNvjofrXhze8PIgPy3viEHbQsHQan-oifDC4)
	(https://mega.nz/#!g2AAWJBK!rs75ZQiuOEAaRItN4x_X1lwJk4iCzbLiP7Mzvq_51kM)  
	(http://www29.zippyshare.com/v/8QQvIqGh/file.html)  

- Veryslow's repack (Hook4, long loading times but lots of content. Japanese style-faces. Has 4x.):  
(mega:///#!TFElzJRR!lss2cTVXR0dtO3cpTFDqC4upWnDf9TkAdYyJCQ4E66s)  

- TK4R (Hook5, preinstalled basics, faster to load. Has 4x. <2gb. Reshade preinstalled. H5 rooms preinstalled. Will perform on older systems like HS/PH does.):  
(https://mega.nz/#!JSZBya7R!8j6mHCNuFTe7JX2l7sc9F_IDE2xGKosyekxoe2BEb3o) (the unzip password is "anon")  

If you use TK4R, refer to this: (https://pastebin.com/3RdM0nK9)  

Within the above paste is additional links to other pastes with more specific info about TK4R.

- Psychonaut repack (Lots of content, but wonky, i.e. no UI replacer, H4, and long loading times. Also good luck with Russian trackers):  
(http://pornolab.net/forum/viewtopic.php?t=2012350) (can't find gdrive links for v3 anymore)  

A multitude of different repacks can also be found on Modsgarden, along with VX.

Some of these are magnet links. That means you need a torrent program to open it. uTorrent is universal. Qbittorrent works fine as well if you prefer that, but some issues have been reported with deluge.   Anything else, read the /t/ sticky.
 
***A2***: Install 7.5/Install Repack:
Just run the .exe and select the path you want it to go to. It is recommended that you install it in c:\ (the default position) and not in the program files folder as that may cause some complications.
 
If you downloaded a repack, extract it into an empty directory, preferably not in program files. Replace any stock Binaries files such as TK17-114.001.exe with modded ones in the repack zips, if those are included.

NOTE: LAUNCH A REPACK WITH THE TK17_LAUNCHER.EXE
IF YOU HAVE AN ERROR SUCH AS "Archives not found", INSTALL THE VANILLA TK17 AND THEN DELETE THOSE GAME FILES

If you wish to install the game from base, then refer to: (https://pastebin.com/7BrXyVKG)
 
---
<h2><p align="center">Additional Steps</p></h2>  

**1a.** Get Hook 5/4 (If not already installed)  
 
Download the current working Hook 4 from this post:  
(http://modsgarden.cc/graphics-enhancements/21/hook4project/1995/915;msg=103050)   

Download "hook4_test9e.zip" from the bottom of the post. Extract all files as you see them into the Binaries folder where you insalled your game.
 
Download the current working Hook 5 from the Hook 5 patreon: (https://www.patreon.com/posts/update-for-hook5-8704104)   
Extract all files as you see them into the Binaries folder where you installed your game.
 
**1b.** Launch and check the hook (this step is important, read it)
Launch the game from the Binaries folder by running the TK17_Launcher.exe file. Launching the game from any of other place may launch the vanilla game (bypassing the hook) instead or cause a crash. Once the launcher has popped up hit Options and MAKE SURE you CHANGE THE OPTION MARKED "RENDERER TYPE" TO "DIRECTX". Again, make sure the renderer is set to DirectX. After that, you can change your resolution size and if you want fullscreen on or off. Once finished in the Options panel, make sure you click the SAVE button at the bottom. It won't look like it does anything but it does. Once finished, click on Free Game (the pair of tits) AND FOR GOD SAKE DON'T FUCK WITH THE PASSWORD FIELDS, just click the START button down at the bottom to launch the game.
 
If the game crashes on launch then you need to choose a different core hook. If the game starts then go to the customization room and look at the textures. Press F9 to toggle the fx file (your variant) on and off. If you get static or there has been no graphical change or that change has been marginal then your hook works, but you need to choose a different fx file.
 
Other than what has been mentioned here and in the troubleshooting section there is really no rhyme or reason for a hook or fx file failing. We can solely attribute it to your graphics card.
 
**1c.** Pick your poison.   
There's plenty of hook files made by others with far more skill than you. You can toy around with the settings by editing your 'main.fx' files with notepad.   
 
It goes without saying that you will have to delete/overwrite the files of hook3 before checking out hook 4 and so on (4 to 5 etc).

---
<h2><p align="center">Extra Info</p></h2>
MODELS, POSES, MODS   

All of these can be found on modsgarden, the first post in each respective thread gives directions on how to install said items. To install models, pop then into /TK Install Directory/Saves/Models. For poses, inside the Saves directory. For texture mods, inside the ActiveMods folder.  

MEMORY FIX  
If your application runs out of memory and promptly crashes and you want that to stop, or you just want to make everything load faster, use the 4GB patch located here:   
(http://modsgarden.cc/4x-hd-textures/25/4x-textures-enabler-mod/1288/msg53019#msg53019)  
Run the exe and patch both the launcher and TK17 exe that are located in the binaries folder. That will allow the game to use 4GBs of RAM instead of limiting itself to 2.  

MOD MANAGEMENT  
A) Download the JSGME mod manager (Generic Mod Enabler)  
From here:  
(http://modsgarden.cc/tools-software/27/jsgme-mod-manager/1314/)  
 
WHY SHOULD I BOTHER?  
Manually Installing mods requires you to save the mod to the appropriate destination in your "TheKlub17" folder, which can be troublesome considering different mods (.txx files, clothes, body mods and so on) go to different directories. Aside from that if you want to check the differences between two mods, enabling one mod and disabling the other more or less boils down to lots of copy paste and deletion of numerous tiny files.
 
The entire process of adding, activating and deactivating mods can be remedied with this commonly used mod manager. This program, when placed in  your "TheKlub17" folder allows you to keep all your mod folders in one place and allows you to easily enable or disable any combination of mods.
 
OK YOU SOLD ME ON IT, WHAT NOW?  
1. Extract [JSGME] Mod Manager directly to your "TheKlub17" folder. You don't need to put its contents in its own folder.
2. Run JSGME.exe. This will create a folder called MODS in the same location.
3. It is recommended that before you delve into modding you apply any scripts or patches to a clean install of TK17. open JSGME, click "Tasks" and "Generate Snapshot of Game Files". This feature will create a reference point in case  you ever need to find out if a particular file is a mod or a core file.
4. Extract the mod you are interested in along with the folder containing it and move it into the MODS folder created earlier.
5. In JSGME, you'll see it in the available mods list on the left. You can activate it by clicking it and then the ">" arrow. Similarly, you can deactivate enabled mods by clicking the mod on the right and then the "<" arrow.
 
Many mods are organised so that they are usable with JSGME. You may however, have to enable mod scripts that complement various mods and make them usable with it. For example R9 Mods require the R9 Custom Addon and NoClip mods. These are applied in the same manner.
 
---
<p align="center">Below is the FAQ Section.</p>
	
---
	
<h2><p align="center"><a name="c">Ingame Help:</a></p></h2>

*Before getting into the messy stuff, it's important to define the game directories.*

> *TK INSTALL DIRECTORY*  
> **Archives**  
> ├─2.114.001 (Where .txx files go)  
> **Binaries**  
> ├─hook_data (Where hook specific config files go. NOT THE HOOK .FX FILES)  
> └─reshade-shaders (Your reshade .inis should be here)  
> **Community**  
> ├─Customizer (Pretty sure clothing presets go here)  
> ├─PoseEdit (Read only poses)  
> ├─Sequencer (Sequence files, to make ingame sex scenes. These require that the poses used in them are available ingame)  
> └─ToyEdit (Native toymaking utility save files. Idk man, make some twisted shit. I'm sure you like your women defiled)  
> **Mod**  
> ├─ActiveMod (This is where envmaps, room/skin/clothes textures go)  
> ├─FaceMate (Data for the internal facegen utility)  
> ├─PoseEdit (Pose folder)  
> └─ToyEdit (Same shit as above mate)  
> **Movies** (Don't fucking export movies from TK17 directly, that's all there's to say)  
> **Music** (Just open up spotify or tidal, jesus)  
> **Save** (This is where all the body/face saves, poses made in poseedit, and model saves go)  
> └─Models (I know, the ModelXXXX naming scheme is wierd. Identify the models by looking at their icons)  
> **Screenshots** (This is where screenshots taken with the ingame button end up. Hook or reshade screenshots will be inside the binaries folder)  
 
- WHERE DO I PUT .TXX MOD FILES (That includes global bodymods, rooms, repacked .txx, and addons in general)?  

(Tk17 Install)/Archives/2.114.001
 
- WHERE DO I PUT SKINS, OUTFITS, ROOM TEXTURES,ETC?  

(Tk17 Install)/Mod/ActiveMod

Room textures appear as additional rooms. They may not appear as the game is picky about the names you give the room texture files.

Same thing with outfits.

Skin textures must always be named by the "FEMALE/MALE_(BODYPART)_(WHITE/BLACK)" filename. If you don't understand, look at the filenames of a skin mod.
 
- WHERE DO I PUT TOYS?  

(Tk17 Install)/Community/ToyEdit  
If the toys are .txx then treat them as .txx files.
 
- WHERE DO I PUT POSES?  

(Tk17 Install)/Save  
or  
(Tk17 Install)/Community/Poseedit  
Poses in Community/PoseEdit are read only.  

- HOW DO I CREATE NEW MODELS?  

To create new model clone a base model (the ugly fuckers in the vanilla game).  
This is only if you have a global body replacer (.txx body file inside archives)  
If you have EMFS or a multiple body mod (Which you can tell by the number of base models with grey body icons that say GE_Female or something), then clone from those base models. The base model will look terrible, but from there, you can modify it to your liking.

Keep in mind that some repacks have face sliders to match a face to a specfic replacer face mod. This is more advanced, however.

- WHERE IS/WHAT IS EMFS?   

Read: (http://modsgarden.cc/3d-replacer-mods/24/3d-mesh-mods-face-litso/2533/)

- HOW DO I USE EMFS TOOL?  

1. Select face Type, then select any of the options for the Face.
2. Tick "Use Person Number". Set it to not conflict with existing files.
3. Choose Body Mesh you like (txx file only). 
4. Set Person Number (this is global, you can't use existing number)
5. Enter base model Person Name you like.
(6) if "Type" is Male, select Details>AvLook>Breasts>Breast_var_man01.
7. Options - tick both "No Clip Camera Mod" (Bad if you want to zoom in real close to them asses) and "Sizer Mod Conpatible".
8. Click "Build".
9. Put that shit in the archives folder. There ya go, cowboy. More women to fuck the daylights out of.

- WHERE DO I PUT MODELS?/WHY DO MY IMPORTED MODELS NOT APPEAR?  

(Tk17 Install)/Save/Models

As for the second question, it's a doosy. There are many ways. The easiest is to make a new model from a base body, and copying all model files (except for base.id) into the cloned model folder.

The EMFS thread in modsgarden.cc explains also explains a more complicated route for the model import process into the game.

Keep in mind that this may not work, but what I have done in the past is that I have cloned a base body model in the models tab ingame, and used the ID within the cloned base body model Base.ID file, and copied that to the Base.ID of the model that I'm importing. It has to do with EMFS/Whatever the fuck multiple bodymod you're using not accepting the base ID of downloaded models. Go figure. If the above method does not work, ask in the thread.

- WHERE DO OTHER MODS (such as clothes) GO?  

In your (Tk17 Install)/Mod/Activemod folder. If it's clothing then feel free to name the folder with the files within anything you like. If it's a room, you must have "R_" in front of the name. (ex: R_OrcKingThrone room)
 
- PEOPLE ARE SHARING MODELS. HOW DO I DO THE SAME?  

Your models are located in (Tk17 Install)/Save/Models folder. They are all named ModelXXXX (where XXXX is their number). To know which one is the model you want to share you just need to open the "choose me" screen in game and pick your model. The number of the clone is mentioned right under her name (for example it may say "Jill clone - 1342". That means that you are looking for Model1342) in the details screen.
Also, keep in mind that models you make may have texture/addon dependencies. Package them if you're a goody-twoshoes.
Explore the folder, .rar up the model then upload that goodness to zippyshare/mediafire/mega. And to modsgarden since without the bulk of their efforts we wouldn't even be able to have it like this.

- HOW DO I GET BACK MY DEFAULT ROOMS/CHARACTERS IN A REPACK?  

If 2003 called back to you, then you have to go into archives and find the .txx which are disabling the default content. Hootie has defined those for his own repack. For others, ditto. For all installs, !0.ETH.Custom.Persons.CleanSlate.txx does remove default models.

- WHY DO MY MODELS MAKE A DUCK FACE IN CUSTOMIZER/FREEMODE?  

Huh, I guess you don't like Instagram models. Jokes aside.  
You need to select any of English voices.  
Voice.txx contains the ingame voices. Some repacks have unpacked and deleted some of the voices, so if you want all the deault ones, then take the voice.txx from a vanilla install.

- WHY IS MY MODEL'S PENIS NOT STICKING INTO HIS/HER MATE'S VAGINA/ANUS or WHY ARE MY POSES FUCKED UP IN TERMS OF HEIGHT?  

This is because the pose author did not make the pose with the heights of the characters you are using in mind. To fix this, enter poseedit and move the bones so that the pose looks alright.

- HOW DO I CHANGE THE SIZE/POSITION OF WIGS?/WHY IS MY HAIR CLIPPING INTO MY MODEL?  

They are treated as hats, so go into the hairsizer tab and modify the values from there. These do not save, so keep that in mind. Hairsizer has the ability to wildy change hair position, hence floating or clipping hair.

- HOW DO I MAKE MY GAME LOOK GOOD?

First of all, refer to the Hook5 instructions on the top of the guide. Follow the install and refer to both the install instructions and the Hook5 hotkeys section below. Second, install SweetFX or Reshade, and mess around with the shaders. Also refer to MG for shared installs of graphics mods. Keep in mind that you should do this while being mindful of your PC specifications, as even the graphics setups used in TK can be demanding. Even to a modern midrange GPU.

BTW, IF YOU USE TK4R, HERE IS A INSTALL SPECIFIC PASTEBIN FOR IT:  
(https://pastebin.com/3RdM0nk9)
 
---
<h2><p align="center"><a name="d">Technical Help:</a></p></h2>

- I GET ARCHIVES NOT FOUND WHEN I START UP THE GAME!  

The game .exe file requires it to be registered inside your computer registry prior to launching. Portable installs ignore this. For non-portable installs, you must launch from the TK17Launcher, install the vanilla game and delete those files, use a multilauncher tool, or make the regedits yourself. 

- GAME CRASHES WHEN I CHANGE THE POSE!  

Blame it on Orca. Maybe Black Viper. Mostly Orca though.  
It's caused by modded exe (seems game crashes when select interactive pose).  
Replace a modded TK17-114.001.exe with a vanilla one.  
But cum on tongue and other addons such as Orca won't work any more.  

- HOW DO I USE HOOK5?  

F4 - hook5 menu  
F5 OR Shift+F2 - reshade menu (modifiable)  
F12 - show customizer  

Inside the hook5 menu, you will find the room definition and the global settings tab. The room defenition tab displays the values of light within a room, while the global settings tab affects hook5 effects such as SAO, Antialiasing, skin wetness, etc.

To manipulate lights, use the dropdown menu on the skinny hook5 menu bar (the one you see when pressing F4), and set it to display lights. Click on the RGB handles of the light to move the light.

To have good lighting, learn some basics about how it all works: (https://www.youtube.com/watch?v=C7w3wpf_XC8.)  

Alt + R - ActiveMod reloading  
Stockings gone?  
Glossiness on the face gone?  
Where's the model's eyeiris?  
If you feel something wrong with models or rooms, your first choice is hitting Alt+R.  
Remember Alt+R is your friend as long as you play TK with any hook.  
To make it clear, ALT+R ALT+R ALT+R ALT+R ALT+R ALT+R. Seriously.  

F2 - show light bounds  
F9 - recreate environment cubemap  
F11 - recompile shader  

PrntScrn - Screenshot (screenshot will be created in Screenshots folder)  
Ctrl + Shift + G - hide GUI (for taking clean SS on reshade)  
 
- HELP! MY CLIENT KEEPS RUNNING OUT OF RAM! / MY GAME KEEP CRASHING WHEN USE 4x / I CAN'T USE DIRECT X!  

Download more ram. Use the 4GB patch. Steal some from a cryptominer (if they even have houses at this point). 
 
- HOW TO INCREASE TEXTURE SIZE (FOR 4X USERS)  

Open the file in Photoshop (or any other Photo Shop esque program you have)  
Image -> Image size -> x00% (x can be 2 or 4 depending on the size of texture)  
Table of texture sizes: Body = 2048x4096  
Hands/Feet = 1024x1024  
Genitals = 1024x2048  
Face = 2048x2048  
DO NOT USE 1x TEXTURES WITH 4x ENABLER. You can identify those by looking at the image size, which will be less than the 4x sizes defined above.  
1x eyebrows look better though, so idk.   
 
- 4GB PATCH:  

(http://modsgarden.cc/tools-software/27/game-files-unpacking-tools/414/msg1198#msg1198)  
Install and run the exe and use it on the launcher and the .exe.  
 
- I HAVE REVERSED ASSHOLE AND PUSSY TEXTURES! (USING SHEMALE BODY REPLACER)  

Simply take the female genital texture and -> copy -> and rename it to Shemale_white. Save and replace the older version.  
 
- HOW DO I INSTALL THE HOOK?  

Extract shader hook files to your binaries folder; replace main.fx file with one you wish to test from the attachment (rename to main.fx).
 
- MY HOOK DOESN'T WORK.  

Do the following:  
Install/update DirectX End-User Runtime  
Set Renderer Type to DirectX in Options (not OpenGL)  
Experiment with different resolution settings (Windowed Mode)  
Remove all mods and/or previously installed graphic enhancements (use a clean install where possible)  
Update your graphics driver (AMD adapters may require 13.3 beta2 drivers; 13.4 drivers appear to work)  
Remove or reset any 3D acceleration profiles (these should be set under program control)  
De-activate any GPU Desktop Managers (e.g. ATI Tray Tools, nVidia nView, etc.)  
Disable SSAO/FXAA in main.fx by commenting lines #define USE_SSAO and #define USE_FXAA_FILTER    
 
Alternatively, try these two different hooks. (DEPRECATED)  
http://www.mediafire.com/download/lzp19l4nn4bftsb/hook_full.zip  
http://www.mediafire.com/download/1paj4kio4pceazh/NEW+ENB+%2B+Skyrim+Shader.rar  
 
And don't forget to set your launcher from OpenGL to DirectX in the settings! If that shit doesn't work, your graphics card isn't supported. Or you're running Wine. Avoid Wine or Winepackager or PlayOnLinux/Mac kiddos, it only works 1/10th of the time. Mostly due to issues with how Hook/Reshade is implemented in Windows.
 
---
<h2><p align="center"><a name="e">Useful Info:</a></p></h2>
 
- WHERE DO I FIND MODELS?  

If it wasn't clear enough before, Modsgarden.cc or the thread.

- HOW DO I MOD?  

If it's something that's not mentioned above, learn modding. No, I won't hold your hand.

- AND THE FUTA?  

Available on modsgarden. Pretty gay though.

- WHERE IS THE HEIGHT SCALE MOD?

No idea. If an anon posts it you're in luck. If not, malchance, étranger.
 
- AND THE LOLI/SHOTAS?  

You shouldn't lewd innocent childern. Jokes aside, never ask for anything like that on modsgarden.  Make your own or find a forum that allows it.  Even posting them in the /tk17/ general is a touchy subject,  the thread gets deleted when excessive amounts of loli gets posted;  the subject matter treads that fine line between loli and cp due to the great detail this game can deliver. Seriously, more real than HS, since TK isn't held back by the cartoony asian face. Check communities that are relevant to loli/shota to get those kinds of TK mods. Or don't, actually.
 
Modsgarden is pretty normalfag and they will leap into a frenzy if you suggest loli/shota mods or clothing or the like.
Despite modsgarden being lewd, they're pretty vanilla/normalfag. Yes, there is foot fetish, furry, pregnancy type shit, but it's not talked about often. Go to modsgarden for the mods, stay in the /t/ generals for the discussion.

- HOW DOES IT COMPARE TO X?

Half of VR sex sims are Unity/Unreal with Daz models pasted into them. They look terrible, they're paywalled, and the devs have no concept of 3D skills other than import/export. Seriously, the fact that none of the games have a thread in /aco/, /t/, or /vg/ speaks to the fact that nobody's duped by them. Not even the Daz stronghold that is /weg/ seems to care about these sex sims.

As for Illusion games, TK17 doesn't suffer from locale issues, but its harder to get good looking faces than in HoneySelect. HS can only create asian faces, so there's that. I'd consider them level, and its really up to personal preference and the small quirks in each game.