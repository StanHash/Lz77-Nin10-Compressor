# LZ77 Compressor

With [Event Assembler] `#incext` support.

Usage Example with Event Assembler 10+:
    
    CompressedDataPtr:
    #incext lz77 fileToBeCompressed.dmp
    
    /* (...) */
    
    POIN CompressedDataPtr

[Event Assembler]: https://github.com/Crazycolorz5/Event-Assembler

# Building

Have QtCreator and/or qmake with QtCore libs ready and build elzee77.pro. Voilà.

# Running

Requires QtCore and whatever compiler-specific runtimes (ex: libstdc++-6.dll & libgcc-stuff.dll with MinGW).

# Thanks

- Nintenlord for making both the original Event Assembler and the base compressor I based my code on.
- Crazycolorz5 and probably other people for updating EA (including adding the useful `#incext` preprocessor command).

:)
