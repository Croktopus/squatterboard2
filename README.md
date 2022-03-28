# squatterboard2

This is an update to the squatterboard project, meant to resolve issues I have with the original. If you're not familiar with the original, the reason I made this was to make a daughterboard with a "squatter" profile than the standard set by the Unified Daughterboard (UDB), since I almost never have room in my cases for a daughterboard with those dimensions.

Electrically, it is compatible with the UDB's pinout, so it can work with any PCB compatible with the UDB. I honestly do not know how it compares for effectiveness because I don't have access to proper testing equipment, and I do know that the routing is not perfectly optimal (I made a couple slight compromises to fit everything a bit tighter and, I'll be honest, to keep the routing clean), but I'm confident that it is good enough (Cunningham's Law inc).

While you are welcome to use this DB as is without any modification, I am not proposing it as an alternative standard, and I encourage you to modify it to fit your needs, because that's why it was made in the first place; as a modification of the UDB concept to fit my needs.

major changes from the original squatterboard:

* Built from scratch in KiCad 6
* Simplified the schematic
* Made it a bit squatter (loses physical compatibility, but I kinda just don't care about that)
* Reorganized libraries, added license, basically just trying to make the whole package a bit more portable so you don't get hit with errors when you download it and try to play around with it - let me know if I failed on that front, this was one of the big reasons I had for redoing this whole thing

major changes relative to the UDB

* Size and shape (obviously)
* Optimized for JLC assembly with basic parts wherever possible (production files are included, though they haven't been tested as of writing)
