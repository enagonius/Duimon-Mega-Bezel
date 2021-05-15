### **Hybrid Presets.**

Hybrid presets use a combination of HSM's shader, (To place graphics and do the screen scaling and positioning.) and standard RA overlays to overlay an additional graphic on top of the shader. The biggest differences are that they use the BASIC-BORDER-WITH-REFLECT base preset, (That has much lower hardware requirements.) and a RA Video aspect of 4:3 instead of 16:9. This reduces the number of pixels in the viewport by 40% and further decreases the hardware requirements.

I have had these presets running as smooth as silk on a GTX 750 2GB (I have not tried them on integrated graphics.)

Like the rest of my presets, they are portable, with intention. They can be used as core, game, or content directory preset simply by moving them to the proper config folder and renaming them.

I have include an example folder "Beetle PSX HW" in the Hybrid presets folder. It contains a "Beetle PSX HW.slangp" which is just a copy of the "Playstation_Hybrid.slangp" renamed to the core name, and a PS1.cfg. This is a content directory override to automatically configure RA for use with the preset. If you are using the Beetle PSX HW core just copy the whole "Beetle PSX HW" folder into your config folder, and load a game. It should just work. You may need to rename the *.cfg to match the name of your ROMs folder.

Using both the presets and the config folder will allow you to use these on your normal RA setup without interference, but I highly recommend that you create an RA installation dedicated to them.

Here is a graphic to help make sense of this.

![](images/tree_hybrid.png)

Right now all of the existing graphics use the same setup, since choice of cores, and the names of ROM folder vary, I will only include the one example. You should be able to open the *.cfg and use the settings in your own configs. I will also leave the renaming of the hybrid presets to the user.

As updates to the shader enable more complex Hybrid presets, I will add presets for specific systems that don't conform to the existing example.



You can also use the traditional methods of creating a content directory preset or rename the PS1.cfg to "Beetle PSX HW.cfg" and make it a core preset etc.

