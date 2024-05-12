# altos-acs8000
I bought an Altos ACS8000-2 and this is my journey

![My Altos ACS8000-2](assets/s-l1600.webp)

## Hardware

The ACS8000-2 is a single board Z80 CP/M computer, with two 8 inch Shugart SA-801, with a serial console port at 9600 8bit NoParity 1 stop bit.

## Software
A CP/M 2.2 boot disk is available for download from archive.org

```
32K ALTOS LOADER VERS 2.21

32K ALTOS DOS VERS 2.21

A>dir
A: MOVCPM   COM : CBIOS32  COM : CBIOS48  COM : CBIOS64  COM
A: PIP      COM : SUBMIT   COM : XSUB     COM : ED       COM
A: ASM      COM : DDT      COM : LOAD     COM : STAT     COM
A: SYSGEN   COM : DUMP     COM : DUMP     ASM : BOOT221  ASM
A: C221LDRB ASM : CBIOS221 ASM : DEBLOCK  ASM : DISKDEF  LIB
A: Z80S     LIB : MODE     COM : CPMSETUP COM
A>
```

Also available is a diagnostic disk.  You'll need this to format floppies.

```
32K ALTOS DOS VERS 1.11

ALTOS DIAGNOSTIC MONITOR VERS 1.1

  ***   D I A G N O S T I C   C O M M A N D   D I R E C T O R Y   ***

        ADXSETUP        COPY            DCOPY           FLPYFORM
        FLPYTEST        MEMTEST         PRNTEST         BOOTCOPY


REQUEST: FLPYFORM


.... ALTOS FLOPPY DISK FORMAT ROUTINE ....
           VERSION 1.11

1.  STANDARD SINGLE DENSITY FORMAT
2.  DOUBLE DENSITY FORMAT FOR CP/M AND DIAGNOSTIC DISKS
3.  DOUBLE DENSITY FORMAT FOR MP/M
4.  END THIS PROGRAM

SELECT FORMAT OPTION BY NUMBER 1


PLACE DISK TO BE FORMATTED IN AVAILABLE DRIVE
REMOVE DIAGNOSTIC DISK IF NECESSARY.
WHEN READY TO PROCEED,
REPLY WITH DRIVE LETTER ("A", "B", "C" OR "D"). A

DISK IN A: HAS BEEN SUCCESSFULLY FORMATTED
```