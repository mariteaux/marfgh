# marfGH

This is a repo for my working copy of marfGH. I build new features and test songs in a chart testing disc that will get used as the template for the actual marfGH volumes. These are all the scripts for that testing disc.

## Contents of this repo
marfGH is built on a *Guitar Hero II Deluxe 2.0* base, but heavily lightened and modified. All Career functionality not related to other modes has been stripped out, as have screens that marfGH has no need for, like the splash screen, high score screen, memory card screens, or anything to do with tutorials. This lightening process is still ongoing. Some vanilla functionality, like the three song speed Practice mode, has also been restored.

Songs, charts, and milos are omitted from this repo so as to not give away early versions of the volume sets. Gotta have something to release, yeah?

### New features
Here are some of the new features I've added to the game so far:

- **Jukebox Mode** - a repurposing of attract mode that allows for SFX-free playback of the disc's songs
- **Random song selection** - let the game choose the song for you
- **Shuffle Mode** - an option to play random songs in perpetuity (especially for Jukebox Mode)
- **Credits gameplay** - an exclusive song to play over the credits scroll in a custom game mode, a la GH3
- **Manual camera cuts** - by calling `[camera_control_on]` in the EVENTS track of a song, the author can force camera cuts with text events as desired
- **Extra crowd control** - The crowd can be set to clap any time the Rock Meter is in the green a la *Rock Band* with `[crowd_clap]` and `[crowd_noclap]` in a MIDI, or cued to cheer at arbitrary times with `[music_end]`

### Features to be added
- **Create a setlist** - A special setlist screen for queuing up songs and playing them all with the same Free Play settings in a row
- **Repurposed cheats** - Many of the debug cheats are useless even to modders and authors, and I'd like to go through and remap them at some point