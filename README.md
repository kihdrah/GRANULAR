# GRANULAR
grain. texture. noise.
A browser-based granular synthesis FX engine built in 2 days using Claude Code — inspired by the Hologram Electronics Microcosm pedal.
Feed it your guitar, synth, or MIDI. It breaks the audio into fragments, scatters them in time, and rebuilds something your ears won't recognise.
<img width="1917" height="927" alt="image" src="https://github.com/user-attachments/assets/2fcdba7a-72a7-4296-ae4e-d8d1dbd3a03f" />


What it does
GRANULAR runs six synthesis algorithms, each with distinct grain behaviour:
AlgorithmCharacterBLURLong overlapping grains → seamless ambient wash. Classic drone texture.SPRAYMid-length grains scattered at random positions → shimmer and diffusion.GLITCHUltra-short grains with per-grain pitch randomisation → circuit-bent digital shards.MICROTight micro-loops clustered around read position → stutter and live drone.STRINGGrains pitch-shifted to harmonic intervals → single notes bloom into chords.CLOUDVery long dense grains → walls of atmosphere. Room-filling, cavernous.
Layering system

FREEZE A — locks the current algorithm as a continuous drone layer
FREEZE B — layer a second algorithm on top of A
Switch algorithms freely while both layers hold

Works on guitar, Seqtrak, MIDI keys, or any audio input via your audio interface.

How to use
No install. No dependencies. Just open index.html in Chrome or Firefox.
bashgit clone https://github.com/[your-username]/granular
cd granular
open index.html
Allow microphone access when the browser prompts — GRANULAR uses the Web Audio API to process your live input.
Basic workflow

Select an algorithm from the grid
Play your instrument — the visualiser responds in real time
Adjust grain size, density, pitch, and mix using the knobs
Hit FREEZE A to lock that texture as a drone
Switch to a second algorithm, FREEZE B to layer on top
Play leads over both frozen layers


Built with

Vanilla HTML/CSS/JS — no frameworks
Web Audio API (ScriptProcessorNode for grain scheduling)
Claude Code — used for architecture, grain engine logic, and UI


Why I built this
The Hologram Electronics Microcosm costs ₹40k. I wanted to understand what's inside it — and whether the gap between "I wish this software existed" and "I could just build it" was actually as wide as I thought.
It took 2 days. It wasn't.

Roadmap

 MIDI CC mapping for hardware knob control
 Preset save/load
 Mobile support
 Export frozen layers as audio file


License
MIT — use it, fork it, break it.

by kihdrah · grain. texture. noise.
