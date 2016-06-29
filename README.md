mplayer-unofficial-patches
==========================

Patches that were ignored by mplayer developers.
You are free to contribute.

To keep repository clean, only files affected by patches are here.
Just copy them over mplayer tree.


demuxer-info-codepage
---------------------
Russian files, especially mp3, usually come with ID tags in random
encoding, so -demuxcp option is added for autodetection of demuxer information
codepage, similar to -subcp. 
Compile with iconv and --enable-enca, use -demuxcp enca:ru:cp1251 (for russian).
Patch was ignored by mplayer developers.

