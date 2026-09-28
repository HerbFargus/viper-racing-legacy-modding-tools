# Viper Racing Mods

This repository is a collection of mods and modding tools for the game Viper Racing

The majority of files are courtesy of Val from Moose Jaw Saskatchewan included from [http://vnovak.com/](http://vnovak.com/)

The main branches are

- Car Tools: tools needed to create and mod new cars
- Car Mods: cars that have already been created that can be extracted into the `Data` folder in Viper Racing
- Track Tools: tools needed to create and mod tracks
- Track Mods: tracks that have already been created that can be extracted into the `Data` folder in Viper Racing

The other branches are various tools, archives, or modding resources that can be potentially useful if you are creating custom mods. 

Some brief tutorials for modding can be found on the [wiki](https://github.com/HerbFargus/viper-racing-mods/wiki)

## Where the tools came from

None of these tools shipped with the game. The table says who made each one and how it
reached the community, as far as the files themselves and first-hand accounts show. The
build date is the link timestamp inside each program; the compiler tells MGI's toolchain
(the Microsoft linker 3.00 that built Viper Racing itself, later 6.00) apart from the
community's.

| Tool | Branches | Built | Made by | How it reached the community |
|---|---|---|---|---|
| `MKRES.EXE` | cartools, tracktools, Retexturing, archive | 1998-08-07, MS linker 3.00 | Monster Games (MGI) | Released by Kevin Combs as part of **RESTools**, for NASCAR Heat modding, "with the help of the Monster Games developers and the producer for the game" ([his iRacing staff profile](https://www.iracing.com/iracing-staff-member-profile-technical-art-director-kevin-combs/)) |
| `MKTEX.EXE` | cartools, tracktools, Retexturing, archive | 1998-08-16, MS linker 3.00 | MGI | RESTools (Kevin Combs) |
| `MKSFX.EXE` | cartools | 2000-04-21, MS linker 6.00 | MGI | RESTools (Kevin Combs) |
| `rescrack.exe` | cartools, Retexturing | 2000-12-04, MinGW (GCC) | Frank P. Wolf: "written by me in C++ based on some code snippets somebody from MGI had dropped" (his site) | Bundled into RESTools; RESTools' own readme lists ResCrack, Mkres, Mktex and Mksfx |
| `MKWORLD.EXE` | tracktools, archive | 1998-09-28, MS linker 3.00 | MGI | Not recorded. Combs' profile says he helped people build NASCAR Heat tracks, but doesn't say he released the track tools |
| `MKILIcc.EXE` | tracktools | 1998-08-18, MS linker 3.00 | MGI | Not recorded |
| `MKSTAMP.EXE` | tracktools | 1998-08-31, MS linker 3.00 | MGI | Not recorded |
| `MKTABLE.EXE` | tracktools | 1998-12-09, MS linker 3.00 | MGI | Not recorded |
| `nhmkworld.exe` | tracktools, archive | 2003-01-02, MS linker 6.00 | Unknown; "nh" suggests NASCAR Heat, but the program names no game | Not recorded |
| `mkfltoa.exe` | tracktools | 2005-07-03, MS linker 6.00 | Unknown | Not recorded |
| `ResClean.exe` | tracktools | 2004-06-23, MS linker 6.00 | Unknown | Not recorded |
| `extract.exe` | archive, tracktools (`mod2track.obt/`) | Delphi | **Sucahyo**: "Sucahyo's PCSX2 game extractor & Viper Racing track tool" (inside the program). The two copies are different builds | Sucahyo's site |
| `mod2quadnoz.exe` | tracktools (`mod2wall/`) | Delphi | **Sucahyo**: "Mod to quad ignore elevation - Sucahyo" | Sucahyo's site |

Frank P. Wolf's own tools (CarMan, TrackMan, LapMan, OptMan, AICarMan, WheelMan) are in
the frankstools branch. His collaborator **Ashes48**, "the hex hacker king" in Frank's
credits, found most of the settings those tools edit.
