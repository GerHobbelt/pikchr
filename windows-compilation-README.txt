
Harry KARADIMAS
May 7th, 2023

Cloned repository https://github.com/drhsqlite/pikchr

Compilation of pikchr for windows 10 64-bits

What was done

Used Visual Studio 2022 (v17.5)

On the command line, typed :

cl /W4 -DPIKCHR_SHELL pikchr.c

As seen in https://pikchr.org/home/forumpost/d4a1db5dcf

There was a harmless warning :

pikchr.c
pikchr.y(5165): warning C4996: 'fopen': This function or variable may be unsafe. Consider using fopen_s instead. To disable deprecation, use _CRT_SECURE_NO_WARNINGS. See online help for details.
Microsoft (R) Incremental Linker Version 14.35.32217.1
Copyright (C) Microsoft Corporation.  All rights reserved.

This warning was also described int the forum post.

The Bitdefender antivirus software mistakenly quarantined the pikchr.exe 
claiming it was infected by "virus gen:variant.lazy 202893"

The whole project with the .exe is in the releases.
