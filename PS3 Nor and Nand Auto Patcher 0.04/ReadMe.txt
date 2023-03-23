------------------------------------------------------------------------
    PS3 Nor and Nand Auto Patcher v0.04         by Rogero    25/Mar/2013
------------------------------------------------------------------------

Changelog:
----------

initial release v 0.01
----------------------
- Compatible with both E3 and ProgSkeet Nor dumps.
- Checking your PS3 Nor Dump if it is Byte-Reversed or No.
- Applying the correct downgrade patches depending on the Dump type detected.
- Eliminating the need to byte-swap the dump in order to apply the patches.
- Making the patching easier rather then using several programs to do it.

v 0.04
------
- Added new Rogero CFW4.40 v1.02 patches.
- No more FSM is needed for downgrading.
- Added detection of non-downgradable "metldr" revisions.
- Added support for Interleaved NAND Dumps (now will patch both Nor and Nand dumps)



How to use:
-----------
Drag and Drop any Nor or Interleaved NAND Dump onto the executable,
it will detect the dump type and patch it accordingly with CFW4.40 patches.


Warning:
--------
This program does not check for the dump validity, 
you must provide a good dump previously checked and verified.

It will patch the dump image even if it's not a 100% valid dump, 
the program only does some minimal checks before patching
assuming that the user have provided a valid dump.