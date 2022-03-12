# Vanilla-Normals-Renewed
This is a port of Vanilla Normals Renewed meant for Bedrock RTX. I absolutely love this pack on PTGI. It's my favorite vanilla conversion pack and the only resource pack I use. This has taken wayyyyy more time than I was expecting (for some reason porting java packs is quite the project) so I wanted others to be able to benefit from my porting and enjoy this pack in bedrock too. If you like it, consider supporting the original creator over at https://www.patreon.com/Poudingue!

Installation: Just download from the releases section or use the main respository to pack it yourself if you want. (Note: pack will only work on Windows 10/11 with an RTX card or RX 6000 card and over).

NOTES:

All textures, specular maps, and normal maps have been ported exactly with some exceptions*, only changes being file structure and the conversion of the java specular maps to bedrock mer maps (which are basically just specular maps with an inverted smoothness channel and swapped color channels).

*The only exception to this are as follows: the glass and ice textures, i modified them to fit more with PTGI's way of rendering colored glass and ice, which required changing the base glass textures to make them more transparent and their normals to make them more inteense. I did this both because I like how PTGI handles glass and you cant see through the default glass textures. It's far from perfect since PTGI transparency just works fundamentally differently than Bedrock RTX it seems, but I tried. The specular and normal maps are unchanged. The dirt specular map, for some reason dirt's specular map has a metalness value of 10 on all pixels even though it shouldnt and the dirt part of the grass side texture has a metalness value of 0, this created a very noticeable inconsistency between the reflectivity of the dirt and grass side textures. I don't think this was intentional and was kind of annoying so I fixed it to remove the metallness value and now the blocks match up. Lava, lava had a maximum reflectiveness value, which wasn't the worst thing ever until you entered the nether. The nether looks like the surface of the sun and parts near lava oceans were so bright they literally hurt my eyes. I toned it wayyy down so its still quite bright in both the nether and overworld but going into a large nether area doesn't instantly blind you.

This pack will not look *exactly* the same as on java as bedrock RTX just works differently (and, dare I say it, not as well) as java shaders, especially PTGI. That being said, I still think the pack looks great on bedrock.

Thanks to bedrock RTX missing a ton of features it really should have like entity pbr and held item pbr, I cannot port any of those unfortunately. If they ever un-abandon bedrock RTX and add these features I will port those textures too.

The official repository (as in the original one that this is a fork of) is missing a ton of normals and speculars cause the creators doing a "big clean" or something. I fished out the latest versions of those textures that got deleted out of Poudingue's commit history to use on my personal Vanilla Normals Renewed folder, meaning that this version is not missing those normals and speculars either as they got ported too since that's the folder I ran the conversion scripts on and re-organized.

I will be keeping this pack up to date with Poudingue's repository whenever they change things.
