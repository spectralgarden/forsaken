```
########   ######   #######    ######   ######   ##  ##   ########  ##    ##
##        ##    ##  ##    ##  ##       ##    ##  ##  ##   ##        ###   ##
######    ##    ##  #######    ######  ########  #####    ######    ####  ##
##        ##    ##  ##    ##        ## ##    ##  ##  ##   ##        ## ## ##
##         ######   ##    ##   ######  ##    ##  ##  ##   ########  ##  ####
==============================================================================
Spectral Garden Studios Presents:        ASTRAL VOCAL PROCESSOR & DECAY SYSTEM
             Developed with JUCE 8.0.14 for Modern VST3 Environments
==============================================================================
```

 User Manual & Spellbook
Welcome to Forsaken. This manual is designed to help you navigate the dark, 
ethereal, and unstable soundscapes of this processor.
1. Quick Start Guide (Your First Ritual)
To get the most dramatic results from Forsaken, it should be used on clean, dynamic 
vocal tracks.
DAW Setup: Insert Forsaken directly on your vocal track, or set it up on an 
auxiliary/return track at 100% Wet Mix.
Input Level: Ensure your incoming vocal signal is peaking around -12 dB to -18 dB. 
This keeps the Black Honey saturation from immediately clipping harshly while giving
the Astral Choke compressor enough signal to grip.
First Preset: Set the preset selector to Voidborne Choir or Wraith Cathedral.
Perform: Speak or sing slowly. Forsaken thrives on space, pauses, and whispered 
consonants. Let the reverse grains and long reverb tails fill the silence between 
words.
2. Control Guide & Parameter Alchemy
The interface is divided into three functional columns designed to shape the audio 
from raw warmth to deep-space decay.
code
Code
[ SPELLBOOK SELECTOR ]   [ BYPASS / ASCEND ]
  ┌──────────────────┬─────────────────┬──────────────────┐
  │ ANALOGUE WARMTH  │  GRAIN ENGINE   │   SPACE & TIME   │
  │                  │                 │                  │
  │  • Black Honey   │  • Reverse Mix  │  • Cathedral     │
  │  • Astral Choke  │  • Reverse Size │  • Dark Filter   │
  └──────────────────┴─────────────────┴──────────────────┘
Column 1: Analogue Warmth (Dynamic Prep)
Black Honey (Warm Saturation)
What it does: Introduces soft-clipping odd-harmonic distortion [2].
How to use it: Keep it low (0.1–0.3) for clean, breathing whispers. Crank it past 
0.7 to mimic a heavily driven, vintage tube preamp or a blown-out dark radio DJ 
microphone.
Astral Choke (Presence Compression)
What it does: A fast-grabbing, heavy-ratio compressor. It "chokes" the dynamic 
range, pulling quiet breaths up and flattening loud transients.
How to use it: At high settings (0.8+), it forces the vocal to feel suffocatingly 
close and intimate, while feeding a highly consistent block of sound directly into 
the reverse grain engine.
Column 2: Grain Engine (The Time-Smasher)
Reverse Mix
What it does: Controls the blend of the real-time reversing grain engine.
How to use it: At 0.0, your vocal passes through normally. At 0.5, you get a 
haunting "double-tracked" effect where your normal voice is accompanied by a ghostly
backward double. At 1.0, the dry vocal disappears completely, leaving only reversed 
syllables.
Reverse Size
What it does: Determines the length of each reverse grain slice (from 30 
milliseconds to 600 milliseconds).
How to use it: Small sizes (0.0–0.3) create glitchy, metallic, stuttering reverse 
textures. Large sizes (0.7–1.0) capture whole words and reverse them in sweeps, 
ideal for long, sweeping phrases.
Column 3: Space & Time (The Void)
Cathedral Decay (Reverb Decay)
What it does: Adjusts the decay time of the internal Feedback Delay Network. At 
maximum, the tail lasts nearly 30 seconds.
How to use it: Increase this parameter past 0.85 to create continuous pads from 
single spoken syllables.
Dark Filter (Dampening)
What it does: A low-pass filter inside the reverb's feedback loop.
How to use it: At 0.0, the reverb is bright and glassy. At 0.8+, high frequencies 
are quickly filtered out with every repeat, making the reverb tail sound deep, dark,
and distant.
Lunar Echo (Delay Time)
What it does: Adjusts the echo interval. It has a built-in slight stereo offset to 
widen the vocal across the stereo field.
Echo Feedback
What it does: Determines how many times the echoes repeat before fading. Keep this 
high (0.7+) for cascading delays.
Wet Mix
What it does: The master dry/wet balance.
3. Sound Design Grimoire (Techniques)
The "Dark Radio DJ" Effect
To get the classic, heavy, low-end vocal texture common in Witch House and darkwave:
Black Honey: 0.7 (Heavy saturation)
Astral Choke: 0.8 (Highly squashed)
Reverse Mix: 0.0 (No reverse)
Cathedral Decay: 0.4 (Short, thick room)
Dark Filter: 0.8 (Very dark)
Lunar Echo & Feedback: Off
Performance Tip: Lower your vocal pitch by 3 to 5 semitones in your DAW before 
sending it to the plugin. The saturation and compressor will turn the pitch-shifted 
signal into a thick, menacing growl.
The "Ghost Whisperer" (Infinite Wash)
To turn a simple spoken word into a sweeping, pad-like background synthesizer:
Reverse Mix: 0.8
Reverse Size: 0.7
Cathedral Decay: 0.98 (Infinite tail)
Dark Filter: 0.5 (Moody high-end roll-off)
Wet Mix: 1.0 (Wet only)
Performance Tip: Whisper a single, sharp word (like "shhh" or "lost") into the 
plugin. Hold the sustain and watch the reverse engine slice the noise, transforming 
it into a lush, dark pad that drifts indefinitely.
4. Troubleshooting
Plugin sounds too quiet: Increase the Black Honey knob. This control acts as a 
pre-gain amplifier and saturation stage [2], boosting the internal volume before it 
hits the compressor.
Reverse delay sounds clicky: Ensure your DAW buffer size is set to 128 samples or 
higher. If your CPU is struggling, the real-time grain crossfading may occasionally 
drop samples.
Reverb tail is too muddy: Lower the Dark Filter control (bringing it closer to 0.3).
This allows more high-mid clarity to escape the feedback loop, brightening the 
decay.
