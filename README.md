# ejUnpacker
x64dbg scripts for finding OEP of packers


## List
### x86
- ASPack v2.xx
- FSG v2.0
- FSG v1.0 v1.1 v1.31 v1.33
- Kkrunchy v0.23a v0.23a2
- MEW11 SE v1.2
- MPress v2.xx
- nPack v1.1.800.2008
- Petite v2.4
- RLPack Basic v1.21. ( Including "aPLib 0.43" & "LZMA 4.30" options )
- UPX v2.xx - v3.xx
- WinUpack v0.39
### x64
- UPX v3.91 -
- MPress v2.xx


## Next
When you find OEP, you can dump and rebuild IAT with Scylla (default plugin for x64dbg).
- (Don't have to set OEP if you already at OEP)
- Click "IAT Autosearch" Button
- Click "Get Imports" Button
- Click "Dump" Button and save it.
- Click "Fix Dump" Button and load what you've saved.
- Then you'll get final result which unpacked and IAT is rebuilded.


## FYI
Personally, I prefer "System Breakpoint" option. So If you don't, Remove first "run" command in each script.


## Ref
[ https://github.com/x64dbg/Scripts ]


## TODO
A lot.

