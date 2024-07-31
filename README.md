 # Vanilla-Normals-Renewed-Bedrock
This is a port of Vanilla Normals Renewed from Java to Bedrock RTX. I absolutely love this pack on PTGI, it's my favorite vanilla conversion pack and the only resource pack I like using. I play on bedrock realms quite a bit so I was tired of having to use all the heightmap based resource packs which i didn't like or the rare normals packs that to me personally weren't nearly as good as VNR and wanted my textures to look just as nice as they did on Java. If you like it, consider supporting the original creator over at https://www.patreon.com/Poudingue. I will be keeping this pack up to date with Poudingue's repository whenever they add or change things.

Installation: Just download from the releases section or use the main respository to pack it yourself if you want. (Note: pack will only work on Windows 10/11 with an RTX card or RX 6000 card and over).

NOTES:

Thanks to bedrock RTX missing features like entity pbr and held item pbr, I cannot port any of those textures unfortunately. If they ever un-abandon bedrock RTX and add these features I will port those textures too.

All textures, specular maps, and normal maps have been ported exactly with some exceptions* where necessary, only real changes being file structure and the conversion of the java specular maps to bedrock mer maps (which are basically just specular maps with an inverted smoothness channel and swapped color channels).

*The exceptions to this are as follows: 

I modified the glass and ice textures to fit more with PTGI's way of rendering colored glass and ice, which required changing the base glass and ice textures to make them more transparent and the glass normal maps to make them more intense. I did this both because I like how PTGI handles glass and ice and you cant really see properly through the default glass and ice textures. It's not perfect since PTGI transparency just works fundamentally differently than Bedrock RTX it seems, but I think it looks pretty good. 

For some reason dirt's specular map has a metalness value of 10 on all pixels even though it shouldnt and the dirt part of the grass side texture has a metalness value of 0, this created a very noticeable inconsistency between the reflectivity of the dirt and grass side textures. I don't think this was intentional and was kind of annoying so I gave them both the same values.

Lava had a maximum emissiveness value, which simply doesn't work well on bedrock. It's emissiveness has been lowered considerably.
