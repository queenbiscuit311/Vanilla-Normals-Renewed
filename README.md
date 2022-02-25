# Vanilla-Normals-Renewed
This is a port of Vanilla Normals Renewed meant for Bedrock RTX. I absolutely love this pack on PTGI. It's my favorite vanilla conversion pack and the only resource pack I use. This took way more time than I was expecting so I wanted others to be able to benefit from my porting and enjoy this pack in bedrock too. If you like it, consider supporting the original creator over at https://www.patreon.com/Poudingue!

Installation: Download an MCPACK from the releases section and install it that way or download the repository as a zip file and rename it to an mcpack file.

NOTES:

All* textures, specular maps, and normal maps have been ported exactly, only changes being file structure and the conversion of the java specular maps to bedrock mer maps (which are basically just specular maps with an inverted smoothness channel and swapped color channels).

*The only exception to this is the glass textures, i modified them to fit more with PTGI's way of rendering colored glass, which required changing the base glass textures. I did this both because I like how PTGI handles glass and you cant see through the default glass textures. The specular and normal maps are unchanged.

This pack will not look the same as it does on java unfortunately. Bedrock handles normals and roughness values differently, and dare I say it, significantly worse than PTGI. It handles normals differently than any java shaders ever, really. You will notice a less pronounced normals effect on many blocks, like glass, and some blocks will not capture the essence of the materials (i have no idea how to word this) properly compared to PTGI. The specular effects are also not anywhere near as pronounced in some instances unless a block is reflecting a light source directly at the screen. There's nothing I can really do about it and it's not a dealbreaker but I thought it should be stated. That being said, the pack is still really, really good and the differences between java shaders and bedrock RTX don't change that.

Thanks to bedrock RTX missing a ton of features it really should have like entity pbr and held item pbr, I cannot port any of those unfortunately. If they ever un-abandon bedrock RTX and add these features I will port those textures too.

The official repository (as in the original one that this is a fork of) is missing a ton of normals and speculars cause the creators doing a "big clean" or something. I fished out the latest versions of those textures that got deleted out of Poudingue's commit history to use on my personal Vanilla Normals Renewed folder, meaning that this version is not missing those normals and speculars either as they got ported too since that's the folder I ran the conversion scripts on.

I will be keeping this pack up to date with Poudingue's repository whenever they change things.
