# Vexyrl-Audio-DAW
A scripting based DAW w/ instrument samples

THIS PRODUCT WILL NOW ONLY BE FOR LINUX SYSTEMS (STARTING MARCH 8, 2026)

<img width="1339" height="825" alt="image" src="https://github.com/user-attachments/assets/ef3f09ba-8804-4d6d-8eb4-268b727f488e" />

# README (IMPORTANT NOTE)

run.sh will start the program on linux.

If you want to set this up like a regular desktop app, just run in terminal "./setup.sh" and you should be able to install the app!

Documentation is all in ReleaseScript.vxrs or if you go to Help -> View Documentation (other documentation file) which contains about everything you can do in this DAW

Or you can just look through all the projects I've tested with this DAW.

<img width="1202" height="828" alt="image" src="https://github.com/user-attachments/assets/236330fa-b280-45fd-9e49-98c3114111e2" />

<img width="556" height="277" alt="image" src="https://github.com/user-attachments/assets/ce52680d-4c02-4849-8b2b-55f3f5741af6" />

# Description

This project is a person project I've been working on since 2/6/2026. It is a scripting based DAW where you can sequence music and play your music.

You can even make your own sample libraries for this if you want! I made sure to make this project as expandable as possible so that you can make the most out of it.

If you want to remove any samples you dont use in like a certain octave, just delete that .ogg file and the sound engine will just stretch it to the nearest note.

You only technically need one sample for an instrument to work.

Patchloader searches for folders in Content/

Your sample library must contain a plugin.txt file that way itll tell the patch loader which instruments to load.

Example:

Content/SampleLibraryName/plugin.txt

contains:

Trumpet

In Content/SampleLibraryName/Trumpet/

is what it's looking for.

You are able to check out how sample libraries are made in the Content folder.
