# Overlay-Hybrid

These are meant to be used as a traditional RA overlay using my Basic_Reflect presets underneath.

Instead of setting the RA video aspect to your monitors aspect, set it to 4x3. This increases shader performance on less powerful systems by reducing the viewport size.

They should work OTB, and you won't need to set any custom veiwport size, the shader handles all the scaling.

The example override assumes you are using the Beetle PSX HW core and that your ROMs are in a folder named "PS1". Use of this override will allow you to use overlays without enabling them globally.

Here are the basic instructions.

1. Set your Retroarch Video Aspect to 4:3.

2. Load some content.

3. Load one of my Basic_Reflect presets. (i.e. \RetroArch\shaders\Mega_Bezel_Community\Duimon-Mega-Bezel\Presets\Basic_Reflect\SONY_Playstation\Playstation.slangp)

4. Save a shader Content directory preset.

5.  Copy my override to your core config folder. (\RetroArch 1.9.7\config\Beetle PSX HW) or, 
    
    * Turn on overlays and load one of my hybrid overlays. (\RetroArch\shaders\Mega_Bezel_Community\Duimon-Mega-Bezel\Graphics\_Hybrid\Overlays\Playstation.cfg)

    * Create a content directory config override.
    
6. Restart retroarch and load some content from the PS1 folder.


The override can be manually edited for other cores and presets or you can go through the motions of creating your own overrides.