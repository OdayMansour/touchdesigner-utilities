# TouchDesigner Utilities

This is a collection of useful Components that I use in my TouchDesigner projects. 

## Components

### audio_processor.toe

Accepts an audio stream as input, outputs:

- Levels: audio levels on low, mid, high, and all frequencies
- Averages: average audio levels over the last _n_ seconds (configurable) on low, mid, high, and all frequencies
- Speeds: continuously increasing values based on the audio levels on low, mid, high, and all frequencies
- Frequency spectrum: output of an FFT on the input audio signal, configurable number of bands

### midi_novation_launchcontrol.toe

Connects to a Novation Launch Control MIDI controller (16 knobs, 8 pads, 8 user templates) and allows to:

- Map min, mid, max values for 16 sliders on 8 user pages
- Add smoothing on slider movement (similar to ease-out)
- Pick up button presses for 8 buttons on 8 user pages
- Send color commands to 8 buttons on 8 user pages
