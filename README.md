# pure-data-additive-synth
My attempt at creating an additive synth using pure data. 

It is has 16 voices of polyphony with an amp and filter envelope for each voice. Each voice has 32 sine wave oscillators that produce harmonics which can be blended in with dedicated sliders. There is an LFO for modulting the pitch of the voices.

Required externals: cyclone 0.4, ceammc 0.8.0

### To do:

- Fix filter envelope
- Have linear attack and exponential decay in the amp envelope.
- Figure out how to save and load presets
- Add pitch shifting delay
- Add oscilloscope to visualize the waveform being played
- Add "random" button that sets all the harmonic sliders to random values
