# pure-data-additive-synth
My attempt at creating an additive synth using pure data. 

It is has 16 voices of polyphony with an amp and filter envelope for each voice. Each voice has 32 sine wave oscillators that produce harmonics which can be blended in with dedicated sliders. Currently, the attack and decay for the envelopes are linear.

Required externals: cyclone 0.4, ceammc 0.8.0

### To do:

- Have linear attack and exponential decay in the amp envelope.
- Make a GUI
- Figure out how to save and load presets
- Add pitch shifting delay
