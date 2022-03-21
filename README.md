# Vanilla-Normals-Renewed-Complete-Bedrock-Port
This is a port of Vanilla Normals Renewed from Java to Bedrock RTX. I absolutely love this pack on PTGI, it's my favorite vanilla conversion pack and the only resource pack I like using. I play on bedrock realms quite a bit so I was tired of having to use all the heightmap based resource packs which i didn't like or other normals packs that to me personally weren't nearly as good and wanted my textures to look just as nice as they did on Java. This has taken wayyyyy more time, effort, and patience than I was expecting (for some reason porting java packs is quite the project), so I wanted others to be able to benefit from my porting and enjoy this pack in bedrock too. If you like it, consider supporting the original creator over at https://www.patreon.com/Poudingue!

Installation: Just download from the releases section or use the main respository to pack it yourself if you want. (Note: pack will only work on Windows 10/11 with an RTX card or RX 6000 card and over).

NOTES:

All textures, specular maps, and normal maps have been ported exactly with some exceptions* where necessary, only real changes being file structure and the conversion of the java specular maps to bedrock mer maps (which are basically just specular maps with an inverted smoothness channel and swapped color channels).

*The exceptions to this are as follows: 
I modified the glass and ice textures to fit more with PTGI's way of rendering colored glass and ice, which required changing the base glass and ice textures to make them more transparent and the glass normal maps to make them more intense. I did this both because I like how PTGI handles glass and ice and you cant really see properly through the default glass and ice textures. It's far from perfect since PTGI transparency just works fundamentally differently than Bedrock RTX it seems, but I tried. 
For some reason dirt's specular map has a metalness value of 10 on all pixels even though it shouldnt and the dirt part of the grass side texture has a metalness value of 0, this created a very noticeable inconsistency between the reflectivity of the dirt and grass side textures. I don't think this was intentional and was kind of annoying so I fixed it to remove the metallness value and now the blocks match up.
Lava had a maximum emissiveness value, which was mostly fine until you entered the nether. Lava oceans looked like the surface of the sun and the lava and bloom was so bright it was actually painful to look at and it significantly discolored the lava texture. I toned the value wayyy down from 255 to 170 so its still quite bright in both the nether and overworld but going into a large nether area doesn't instantly blind you.

This pack will not look *exactly* the same as on java as bedrock RTX just works differently (and, dare I say it, not as well) as java shaders, especially PTGI. That being said, I still think the pack looks great on bedrock.

Thanks to bedrock RTX missing a ton of features it really should have like entity pbr and held item pbr, I cannot port any of those unfortunately. If they ever un-abandon bedrock RTX and add these features I will port those textures too.

I will be keeping this pack up to date with Poudingue's repository whenever they add or change things.
