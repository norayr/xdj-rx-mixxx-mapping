how to use
==========

put xml and js file to .mixxx/controllers directory, if you run it on Linux.
on other systems there is a bit different path, but you probably know it.

what works
==========

I think I mapped almost everything, and I can work with this mapping.

Mixxx design differs from XDJ-RX design.

One example is, quantize button is one for all decks on XDJ-RX, while Mixxx has the separate quantize buttons for each deck.

Other example, Mixxx has the super effect button, which controls all the selected effects.
XDJ-RX cannot mix so called "sound color fx", i. e. "gate/comp", "filter", "noise", "crush" with each other - the blue buttons on the left side of the mixer. The same effect is chosen for both channels.
However you can mix one of "color fx" with one (and only one) of the effects, located on the right side of the mixer - echo, spiral, flanger, pitch, etc.

In Mixxx, you can use several (and any) effects simultaneously. For that you select some effects (well, choose and add those first), and then use super knob to manipulate em all.

So I decided to use the loop slice buttons to enable-disable (chosen) effects, and then I use the color fx knob as a super knob.

tempo button changes the tempo slider diapason as:

-3 to +3 BPM, 

-6 to +6 BPM,

-12 to +12 BPM.

what doesn't work
=================

If you are a Linux user, currently Linux (ALSA) doesn't recognize XDJ-RX's soundcard. And I guess will unlikely recognize.
So for previews via headphones, you need another sound card. (one card for your master output, let's say your laptop card, and one card to route previews to your headphones)

Also, XDJ-RX doesn't have MIDI OUT, which means, it is not possible to control LEDs via MIDI signals, and those won't flash, go on/off. What I personally will miss, and that was one of the main reasons to buying this exact model - LED animation on a jog wheel, which shows that this "turntable" is currently playing.

And the last - difference from the real layout of XDJ-RX device:
You put hot cues by using hot cue buttons, but you clean them, by pressing same buttons with 'shift'.
