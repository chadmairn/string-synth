# String Synth

A browser instrument. Two hands play five virtual strings, and your face plays the effects.

## How it plays

- Desktop: hold your hands up to the camera. Each pair of fingers (thumb to index, and so on) is one string. The distance between the fingers sweeps the string's filter.
- Phone: one hand plays four strings. Your face drives the effects: head left and right moves the filter, head up and down moves the pitch, mouth open adds reverb, head tilt pans the sound.

## Extras

- A patch bay sequencer (desktop): an 8 step sequencer with a quantizer, and click to draw cables from sources like the sequencer clock, the LFO, or your face position to destinations like cutoff, resonance, reverb, delay, and pan.
- Hold and drone buttons keep a string ringing.

## Run it

Serve the folder over HTTPS (the camera needs a secure page) and open `index.html`. It loads p5.js, MediaPipe Hands, and MediaPipe Face Mesh from CDNs. No build step, no install.

Built at the SPC Innovation Lab.
