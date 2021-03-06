This is the TinyBasic ROM I want to install on my Z80-based home computer.
I use the Z80 port of Obijuan which I forked and then modified.
Obijuan's code is already quite size-optimized, but there is space for 
further improvement (which I already started).

The next step will be to make the interpreter modular to make it easier to
understand. The manual of z80asm supporting this is here:
* https://www.nongnu.org/z80asm/directives.html
* https://www.nongnu.org/z80asm/usage.html

Then, possibly work towards more compilation and less interpreting. 
Of course, as the I/O interface evolves this may evolve, too.

Z80 instruction set
* z80 manual search on Google
* http://clrhome.org/table/
* http://z80-heaven.wikidot.com/instructions-set

Z80 assembler
* http://savannah.nongnu.org/projects/z80asm
* http://download.savannah.nongnu.org/releases/z80asm/

Circuit building aspects
* https://www.google.com/search?client=firefox-b-d&q=ttl+decoupling+capacitor
* http://www.bestsoldering.com/how-to-cut-veroboard/
* https://www.eevblog.com/forum/projects/bypass-caps-for-diy-z80-single-board-computer/
* https://electronics.stackexchange.com/questions/72020/how-to-set-up-an-oscillator-for-simple-frequency-generation
