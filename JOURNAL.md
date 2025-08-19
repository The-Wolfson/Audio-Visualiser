---
Title: "Audio Visualiser"
Author: "Joshua Wolfson"
Description: "A desktop device to control Spotify, with some bonus nifty visuals."
Created On: "16/8/2025"
---

Total Time: **13 hours**

# 16/08: Research...

I've been wanting to make something for grounded, but I just came up with an idea for an audio visualiser that connects to Spotify.
So far I know that i'll be using the led-matrix modules for the audio visualisation component. Then I'll also have back/pause/skip buttons, and a volume knob. While I'm at it I might as well add a way to see what song is playing.

**Total time spent: 5h**

# 17/08: PCB...
I started laying out the schematic, the real struggle was sourcing footprints. Once that was done, the problem was figuring out how to reduce the number of GPIO pins used from 12 to 11. The solution I came up with was to use a resistance ladder, but I'm unsure if this will work, I'll reach out on the slack to get some advice.

**Total time spent: 5h**

# 17/08: 3D CAD...
So, thanks to the advice of [Toby CM](https://github.com/tobycm), I updated my keyboard matrix from using resistors to diodes. This should make it alot easier to manage.
After that I finished wiring, and started case design. The case is fairly straightforward, a couple of bevels to polish it off and Bob's your uncle!
Now to submit...

**Total time spent: 3h**
