# ShipwaifuDS
A homebrew game for Nintendo DS... and Nintendo 3DS (given you can boot DS homebrew in DSi mode, or you have a DS flash cartridge)

## Why?
I have a strong interest in [Kantai Collection](http://en.kancollewiki.net), which is based around you playing as an admiral (commander) of a fleet of shipgirls. Shipgirls are basically personifications of sunk ships in the past (ie. Imperial Japanese Navy, Royal Navy, etc) brought back to life that are fighting corrupted abyssal versions of themselves to bring peace to the world.

## Help wanted!
TODO.

## How To Play
TODO.

## Build your own copy of ShipWaifuDS
TODO.

## Screenshots
TODO.

## Why Nintendo DS? Isn't that old?
I originally tried to start this project on the ESP32 using Bitluni's Composite Video output library but after lack of documentation and the fact that the code required working with the Arduino IDE (or PlatformIO), I felt overwhelmed. Sure, it would be nice to make a game on the ESP32. But since you only have around 3.5MB of Flash Memory to put everything in without rigging up a microSD card and using filesystem read calls, you run out of space quickly. Also audio-wise there's no real way to play music on the ESP32 (no MIDI synthesis or lookup tables in Bitluni's library yet) apart from trying to compress music to fit into ROM. Yeah, good luck with that unless I wanted 3 second loops.

Mind you, Bitluni is a great person, and I'm not trying to take a crap on him. Definitely not - I want to make that clear.

I also cannot be assed to write my own libraries for the ESP32 because I'm a C# game developer and I'm only doing this C/C++ homebrew ROM as a challenge over time. One of the other reasons I chose the DS is that libnds (which is the library I'm using) is mature and has a lot of example code that can get me up and running fairly quickly. Of course, it's not going to be like building Rome in a day.

## Copyrights
TODO.

## Credits
- English KC Wiki Discord
- C2/DMM/KADOKAWA for Kantai Collection
- Libnds Team
- Ko-fi Donators
