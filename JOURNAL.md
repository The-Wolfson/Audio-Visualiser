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
https://components101.com/displays/max7219-8x8-led-matrix-module
https://www.lcdwiki.com/0.96inch_OLED_Module_MC096GX#Hardware_description

**Total time spent: 5h**

# 17/08: PCB...
I started laying out the schematic, the real struggle was sourcing footprints. Once that was done, the problem was figuring out how to reduce the number of GPIO pins used from 12 to 11. The solution I came up with was to use a resistance ladder, but I'm unsure if this will work, I'll reach out on the slack to get some advice.
<img width="1734" height="1370" alt="Screenshot 2025-08-18 at 10 48 45 pm" src="https://github.com/user-attachments/assets/c7bf677f-aa97-47ea-b276-19cde24c7f35" />

**Total time spent: 5h**

# 17/08: 3D CAD...
So, thanks to the advice of [Toby CM](https://github.com/tobycm), I updated my keyboard matrix from using resistors to diodes. This should make it alot easier to manage.
After that I finished wiring, and started case design. The case is fairly straightforward, a couple of bevels to polish it off and Bob's your uncle!
Now to submit...
<img width="860" height="621" alt="Screenshot 2025-08-19 at 9 33 24 pm" src="https://github.com/user-attachments/assets/09977c38-3bcf-48e0-897a-ed3f1f7ce2aa" />

**Total time spent: 3h**
