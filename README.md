# Fae_Graphics
The all new way to make a 2D game.


This library includes both JFrame creation, which uses the monitor's resolution and soon a customizable resolution, as well as a scale system
This scaling system is adaptable so your program will look EXACTLY the same on any monitor resolution, as long as the aspect ratio does not change

#####This library is NOT DONE and I highly recommend not using it. Frankly even if it was done there are much better ways to make 2D games in Java.

TODO: add new aspect ratios.

####What is this?
This is some of the code I used in Damned Dwarves Deux and Heroes of Trampoline Horror. It comes in four parts. A Sprite which can be used to create and transform images. (This part was mostly made off of a tutorial). A Base Panel which other panels can implement and this class includes variable framerate. This feature is important if the person has a computer with an insufficient processor to handle the game at the specified framerate. It is a little bit of spaghetti code but not quite as spaghetti as the Window Loader. The Window Loader can load windows but it is a little bit of spagetti code and needs to be improved. Finally there is the Sprite Loader which stores an array or hashmap of sprites which can be called by ID or name. This last one is significantly faster than reading sprites from the disk so it is highly recommened that you implement it. Though it is technically optional.


