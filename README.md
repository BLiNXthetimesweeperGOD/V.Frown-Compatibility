# V.Frown-Compatibility
A (work in progress) compatibility list for the V.Frown (V.Smile) emulator.

# General issues (known to happen in almost every game)
- Controls

Sometimes, your last input will keep going even after releasing a button.

Sometimes, the game you're playing will stop responding to inputs for up to around 10 seconds.

Sometimes, inputs will be delayed. (In some cases, it's just a problem with the game though - be sure to test on real hardware too in this case!)

Some games will lock up if you press buttons too fast.

- Audio

It will lag a bit if you don't increase the CPU clock speed to 27.54 MHz. Any higher and the sound will skip.

Some sounds don't play properly.

Some sounds just don't play at all. Happens in almost every game.

8-Bit PCM decoding is still a bit rough/has a bit more noise than intended.

ADPCM decoding still isn't entirely accurate (certain voice clips will have their lower frequencies get louder as they end as an example)

- Visuals

Certain graphics don't load correctly and display as a garbled mess of tiles across the entire screen.

Transparency doesn't work yet. I'll only list this as an issue if it gets in the way of gameplay.

- Gameplay

Sometimes, your controls will stop working entirely, requiring you to restart the emulator.

# Alphabet Park Adventure (USA) (Original Version)
- Status

Playable to 100% completion. Not perfect.

- Audio

The intro cutscene plays garbage data if reloaded after already playing it once

# Shrek: Dragon's Tale (USA)
- Status

Playable to 100% completion. Not perfect.

- Audio

Has some issues with certain channels not playing for a few seconds after a song starts.

Certain songs (like Forest Search) don't play their audio samples right.

- Visuals

Transparency doesn't work, leading to a few items being hidden behind walls.

Sprites sometimes render on the wrong layer for a frame or two.

- Gameplay

You need to skip the BIOS animation to get the game to boot.

Can be played to 100% completion but with a few minor issues.

You might not be able to see Shrek/Fiona in certain parts of Castle Sneak.

You can't jump diagonally in Dragon's Castle Showdown without releasing the arrow keys first.
