# PCSX2 Configs 1.7.0

These are personal configs I made from scratch with v1.7.0 in mind, therefore it uses OpenGL since DirectX multisampling is deprecated. In return I use an internal resolution 4 times bigger but if you have the power resources to spare I recommend to go 5 times for ultimate antialiasing as I have on my own setup. The other safe setting to increase accuracy is Accurate Blending, here is set to medium while I normally use High on my 4790K, GTX1070 setup. The settings are based on the Safe preset and has Vsync enabled.


Change the next settings for a quality boost (RTX 2060+ recommended):

accurate_blending_unit=3

upscale_multiplier=5


Additionally my setup is based on PAL titles, NTSC titles have many more 480p patches than PAL so all you need to do in such cases is set:


interlace=0

EnableCheats=enabled