# Appalm ][

[Welcome to the Apple II emulator for PalmOS](http://palmapple.sourceforge.net)

## Authors:

Hilary Cheng :

David Schmenk:

Web Sites    : http://sf.net/projects/palmapple

Public Forum : http://sf.net/forum/forum.php?forum_id=88936

## License:
Appalm][ Licenses is GNU GPL. Please go to this links for more
details Appalm][ is based on YAE so that we can port to PalmOS
Platform. Appalm][ cannot be used for sale unless there is an
agreement with the authors. Please contact the author before
any sale.

Appalm][ is an open source software.  Anyone is free to modify
the source code and contribute to it. All the users are free to
use this software. But the authors are not responsibile for any
damage by THIS SOFTWARE. Please try it at Your Risk!

## Preface:
Because  68000  based  Palm  devices are barely faster than the
Apple  ][,  emulation  performance may be less than stellar. An
overclocking  utility  will  go a long way to make the emulator
more useable on anything less than a 66Mhz Clie 665C.

## Introduction:
What would be better than being able to take your beloved Apple
][ with you, including most of the software you had for it, all
in  your  pocket?  Here  is your chance. The Appalm ][ emulator
brings  a  64K Apple //e, no 80 column card, and 2 disk drives,
to your Palm OS based PDA. Disk images can be uploaded into the
internal  Palm  memory  or  a  memory card (think how many 140K
floppies  fit  on a 128 MB memory card :-) ) Joystick emulation
is provided using the hard keys available on most Palm PDAs. If
you  have  one  of  those Zires without all the keys, then life
sucks for you. The Sony HIRES screen is supported (in color!) -
and  looks great too. The Sony Game Controller works very well.
Highly recommended.

## Installation:
You  need  to  install  the  emulator, appalm.prc, plus the ROM
files  apple2e.rom  and slot6.rom. Pick a disk image (currently
must  be  .DSK  fomat)  and use the DSK2PDB utility to create a
PalmOS  DB  of  the  disk  image.  A '-r' flag can be passed to
DSK2PDB  to  create  a  nibblized  disk  image  which  can load
slightly  faster  on the Palm but takes up 220K vs 140K for the
raw  data.  The  standard  format database performance has been
improved to the point where I don't know why you would want the
raw format.

## Running:
The  basic  features  of the emulator are available through the
menu. Special keys and joystick options are settable there. You
can  return  to  the  Palm Launcher and run other applications.
When  you  come back to Appalm, it is in the same state as when
you  left  it.  Some  of the Palm buttons have been hijacked to
provide useful feature for the emulator. They are:
	Calculator	- ESC key
	Find		- CTRL-C
	Appointment	- Joystick button (1 or 2)
	Memo		- Joystick button (1 or 2)
	Phone/ToDo	- Joystick X axis
	PgUp/PgDn	- Joystick Y axis
A  type-ahead  buffer  is  implemented for use with an external
keyboard. You can keep typeing without losing characters.

## Development:
This   is   a   very   preliminary  version  meant  more  as  a
proof-of-concept.   More   features  and  performance  will  be
improved upon. Disk performance is very good now and writing to
the  disk  image is supported. Sound support would be nice if I
could  figure  something workable out. Color support for lo-res
(160x160) Palms is in the works.

## Conclusion:
I wanna say thank you to David Schmenk for enhancement of Emulator
and prepare all the works of Appalm][.

And  I  can  thank Hilary for doing all the initial development
that  laid  the  groundwork for my work. Its much easier if you
have something that already works when developing new emulation
components.


