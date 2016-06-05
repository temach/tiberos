# tiberos
Simple kernel

Also useful books: http://wiki.osdev.org/Books#Compiler_Theory

Usefull resources:

0. Some books:
  * http://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf
  * https://pdos.csail.mit.edu/6.828/2014/xv6/book-rev8.pdf
  * https://www.inf.ethz.ch/personal/wirth/ProjectOberon/PO.System.pdf
  * http://wiki.osdev.org/Bare_Bones

1. Should you use .elf or .bin files for your kernel and programs: http://stackoverflow.com/questions/34129461/should-i-make-my-own-os-kernel-elf-or-raw-binary

2. Elf files:
  * Hand compiling an .efl file: https://web.archive.org/web/20140130143820/http://robinhoksbergen.com/papers/howto_elf.html
  * Writing it to disk file: https://github.com/suspectpart/misc/blob/master/elf.py


4. Making iso from compiled kernel code so it can be burned to CD/USB: http://www.gnu.org/software/grub/manual/html_node/Making-a-GRUB-bootable-CD_002dROM.html 

5. Grub booting: 
  * http://thestarman.pcministry.com/asm/mbr/GRUB.htm
  * http://unix.stackexchange.com/questions/259143/how-does-grub-stage1-exactly-access-load-stage-2
  * http://www.dedoimedo.com/computers/grub-2.html

6. This is programming for UEFI, but linker flags are still useful: http://www.rodsbooks.com/efi-programming/hello.html

7. Boot process (grub/lilo/windows/etc.) nice details: 
  * http://www.ibm.com/developerworks/linux/library/l-linuxboot/l-linuxboot-pdf.pdf
  * https://neosmart.net/wiki/mbr-boot-process/

8. Booting with a chainloader instead of via multiboot: http://stackoverflow.com/questions/17909429/booting-a-non-multiboot-kernel-with-grub2

9. Working example of bare metal tetris on x86: https://github.com/programble/bare-metal-tetris 

10. Simple OS to fit into 512 bootloader sector: http://mikeos.sourceforge.net/write-your-own-os.html
