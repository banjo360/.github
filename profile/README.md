# Banjo-Kazooie XBLA research project

This organisation is to fiddle with the XBOX 360 version of Banjo-Kazooie and maybe end up with a decompilation. In doing so, we create tools that might help other XBOX 360 enthusiasts to make modifications to other games.

## Repositories

### dump-diff

A tool that disassembles 2 blobs of compiled code and show the differences in the resulting assembly.

### bk360

The main repository of the decompilation project.

### Ghidra converter

Generate a listing of all the functions from an XML file exported from Ghidra to a format used by other tools (e.g. coff-linker).

### coff-linker

Takes an .obj file containing your compiled C code, extract the data and functions into separate .bin files, then patches their relocation symbols.

### split360

Splits and merges a .xex file based on a YAML definition.
