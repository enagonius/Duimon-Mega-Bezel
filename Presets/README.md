
# HSM Reflection Shader Graphics Presets

These are presets for the graphics I have created for HSM's Mega Bezel Reflection Shader.

They are compatible with v0.9.00 of the shader and, barring some unforeseen complication, should remain compatible with future versions. They use the "Logo" versions of my graphics.

The path to the graphics has changed from ..Retroarch/overlays/bezel/Logo" to "..Retroarch/overlays/bezel/Duimon/Logo" to allow other artists graphics to be in the same path.

For now I have created presets for only the "Standard" base presets, most use the DrVenom CRT but some use the LCD.

These "Standard" presets use only the generated bezel and frame, with Vintage monitors and custom bezels, (With LEDs and other bling.) being reserved for my upcoming "Advanced" presets.

Other limitations include Decals not being scale-able. Please see HSM's shader thread and the shader readme for more extensive information on the differences between the base shaders.

To keep installation simple and cohesive, I have archived the presets into a "Presets.zip". Inside the zip you will find a "shaders" folder. Simply extract that folder onto your existing shaders folder and everything will be in the correct place.

Inside your shaders folder you will now see 4 presets:

1. Duimon_Advanced.slangp
2. Duimon_Advanced_LCD.slangp
3. Duimon_Standard.slangp
4. Duimon_Standard_LCD.slangp

You will also see a "Duimon" folder.

For these presets to work, the four presets MUST remain in the shaders root folder. The "Duimon" folder can be moved anywhere you want as long as it is under the root Retroarch path, although I recommend leaving it where it is to make future updates painless.

Inside the "Duimon" folder you will find "Standard" and "Advanced" folders. For now only the Standard is populated.

These presets make use of the new Simple Presets feature in RA and new path syntax. This allows you to, for example, copy one of the presets into a core config folder and rename it to a core, game, or content directory preset. Please see RA documentation for information on these types of presets. You can also, of course, use the traditional method of creating these presets.

I have taken the liberty of creating game presets for the Vectrex games. They are in a "VecX" folder inside the "Standard" folder. Copy this folder to your config folder and, as long as your roms share the same names as the presets, they will automatically work. I have used the standard No-Intro naming convention. The overlays provided are the standard available on Libretro, with a few custom exceptions and can be found on my GitHub in a "Vectrex_Overlays_Standard" folder and must share the same folder structure as my repo. (i.e. "Vectrex_Overlays_Standard" must be inside "Duimon" along side the "Logo" folder. For now they are 1080p and raster.

Here is a shot of the Vectrex in action.

![](images/Armor..Attack%20(World)-210405-164644.png)

I have increased the phosphor persistence, glow, bloom, and eliminated scanlines to try and help simulate a vector display.

It is with great joy that I celebrate the new shader release with the release of my Vectrex graphic. I hope it brings you equal joy.


The advanced presets will be a much greater undertaking, and involve quite a bit of graphics wizardry. They will include a few fancy bling-filled vintage monitors, scale-able handhelds with independent backgrounds, (I will include a set of these you can choose from or you can use an image of your own.) a phosphor layer on vintage TVs, custom HDR derived screen reflections, color adjustable bodies on some handhelds and consoles. and many things I have yet to discover myself.

I anticipate a few growing pains. Please don't hesitate to post on my forum thread when you run into problems or discover any mistakes I am sure I made.


