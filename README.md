# Parrot::Embed

This is an embedding interface to use Parrot from Perl 5.

Be afraid.

# Installation

To install this module, run the following commands:

    perl Build.PL
    perl ./Build
    perl ./Build test
    perl ./Build install

If you're building this within the Parrot tree (that is, if you don't have a
Parrot installed somewhere else), you need to set the proper environment
variable to tell your dynamic linker where to find the `libparrot.so` or
`libparrot.dll` or `libparrot.dylib` file to load.  I believe this is
`LD_LIBRARY_PATH` on Unix-like systems and `PATH` on Windows.

# Copyright and License

Copyright (C) 2006 - 2011 Parrot Foundation/chromatic

This program is free software; you can redistribute it and/or modify it
under the same terms as Parrot itself.
