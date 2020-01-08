# fits
C fitsio library: pre-compiled binaries for Windows 10 in 32 bit and 64 bit version.

Compiled with Visual Studio 16 2019.

Simply:
-> copy the files into your program directory,
-> include them via #include "fitsio.h",
-> compile it via 
     gcc your_program.c -L. -lcfitsio
   or
     cl /MD your_program.c cfitsio.lib

If you get a linker error you have most likely chosen the wrong version (32 or 64 bit).

See more details here: https://heasarc.gsfc.nasa.gov/fitsio/


