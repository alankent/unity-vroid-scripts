# unity-vroid-scripts

WARNING: This code is very old now, and I stopped using it in favor of using HANA_Tool (which costs a few dollars). Their code works reliably - mine crashes Unity after a while. I probably have the memory management not quite right. This these files are referenced from an old blog post, so keeping available.

* CopyBlendShapes.cs - Simple code showing how to read and write blend shape definitions (does a verbatim copy).
* CleveryBlendCopier.cs - Experimental Unity C# script to copy blend shapes from one VRoid characte Face to another, even if the meshes have been modified. (It does some expressions okay, but fails around the mouth.) See also [this blog](https://extra-ordinary.tv/2020/09/07/copying-blendshapes-in-unity-with-a-script/)
* AddIFacialMocapBlendShapes.cs - Experimental Unity C# script to generate blend shapes needed by ARKit (and ifacialmocap.com) from the default blend shapes from VRoid Studio (no use of Blender or other tools is required). Takes 5 to 10 minutes to run.
