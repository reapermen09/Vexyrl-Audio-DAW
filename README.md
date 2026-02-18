# Vexyrl-Audio-DAW
A scripting based DAW w/ instrument samples

# LINUX INSTALL

If the project doesn't work the first time (which it usually doesnt)

This is the fix if you get the "file too short" error.

Download: https://www.sfml-dev.org/files/SFML-2.6.0-linux-gcc-64-bit.tar.gz

And extract the archive

go to SFML-2.6.0/lib/

and you'll need to copy and paste (replace all)

"libsfml-audio.so"

"libsfml-audio.so.2.6"

"libsfml-audio.so.2.6.0"

"libsfml-system.so"

"libsfml-system.so.2.6"

"libsfml-system.so.2.6.0"

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

# Windows Example:

<img width="640" height="640" alt="image" src="https://github.com/user-attachments/assets/6fe366a0-4eb5-42c8-9825-4418805e15ab" />

# Linux Example:

<img width="997" height="771" alt="image" src="https://github.com/user-attachments/assets/860fcc74-81d3-4316-9ce4-c6bf55fe4f5e" />

<img width="1000" height="768" alt="image" src="https://github.com/user-attachments/assets/4d6e80a4-098e-45a2-a8ab-37be609b23ac" />
