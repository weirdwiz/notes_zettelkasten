Tags: #bootloader #makefile
From: [[202009190936 CBZ CBNZ]]

---
The Makefile compiles and links together to create an image called `kernel.img`. Which is booted on the raspberry pi.

The makefile lists all the object files as prerequisite, thus making the Makefile trigger the object file target.

The objects file are then linked together using `linker.ld` and get's outputted onto a file called `kernel8.elf`



---
### See Also
- [[202009231114 making object files of C files using Makefile]]
- [[202009231211 gcc flag -Wall]]
- [[202009231213 gcc flag -O]]
- [[202009231230 gcc flag -nostdinc or c++]]
- [[202009231234 gcc flag -nostartfiles]]
