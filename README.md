# Vexyrl-Audio-DAW
A scripting based DAW w/ instrument samples

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
