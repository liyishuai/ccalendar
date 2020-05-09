Chinese Calendar
================

A Chinese calendar implemented with astronomical algorithms by referring to
[Calendrical Calculations: The Ultimate Edition (4th Edition)](http://www.cs.tau.ac.il/~nachum/calendar-book/fourth-edition/)
by Edward M. Reingold and Nachum Dershowitz.

This utility is derived from the current
[calendar(1)](https://gitweb.dragonflybsd.org/dragonfly.git/tree/HEAD:/usr.bin/calendar)
presented in
[DragonFly BSD](https://www.dragonflybsd.org/).


Installaion
-----------
Requirements:
* GCC
* GNU Make

Build and installation:
1. `make [PREFIX=/usr/local]`
2. `sudo make install [PREFIX=/usr/local]`

*NOTE*: Use `gmake` on BSD systems.


References
----------
[RD18]
Edward M. Reingold and Nachum Dershowitz,
*Calendrical Calculations: The Ultimate Edition*
(4th Edition).
Cambridge University Press, 2018.
ISBN: 9781107057623


License
-------
The 3-Clause BSD License

Copyright (c) 2019-2020 The DragonFly Project.
