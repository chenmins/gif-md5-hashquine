GIF MD5 hashquine
=================

![GIF MD5 hashquine by Rogdham](rogdham_gif_md5_hashquine.gif?raw=true)

    $ md5sum rogdham_gif_md5_hashquine.gif
    22d058dd8aad588cadeadf33e6c9977e  rogdham_gif_md5_hashquine.gif


What is a hashquine?
--------------------

“Hashquine” is a term coined by
[foone](https://twitter.com/Foone/status/839213095901765632)
meaning “file that show their own hash”.


Wait, I thought someone made one before
---------------------------------------

Indeed! [spq](https://twitter.com/__spq__/status/838583044260904960)
created a GIF MD5 hashquine before, but I did not know at that time.


How did you do it?
------------------

Please read [my detailed write up][writeup] or look at [the source code](src)
use to generate it.


[writeup]: http://r.rogdham.net/30


What about the licence?
-----------------------

The GIF file is released under the [CC0][] licence, as seen in the strings of
the file:

    $ strings -n 20 rogdham_gif_md5_hashquine.gif
    Copyheart Rogdham, 2017
    <3 Copying is an act of love. Please copy and share.
    Released under the CC0 1.0 universel licence
    See https://creativecommons.org/publicdomain/zero/1.0/deed.fr

The source code is also released under the [CC0][] licence, making it a free
software. See the header of each file for more information. Use at your own
risks, if possible for good or interesting things.


[CC0]: https://creativecommons.org/publicdomain/zero/1.0/deed.fr
