---
layout: default
---

[About Us](./about-us.html) | [Calvin CS](https://computing.calvin.edu/) | [Senior Projects](https://computing.calvin.edu/) | [Final Report](./assets/docs/final-report.pdf) | [Presentation](./presentation.html)
# Vision
## Problem
Adaptive music is a recent paradigm of composition that accounts for the non-linearity of video games. Using techniques like horizontal scaling, a song can slowly transition into another song; and vertical techniques can re-orchestrate the current song. These techniques make for a more immersive experience as the soundtrack adapts to a player’s surroundings.

Creating adaptive music is not a trivial problem, and existing products provide software solutions to compose this type of music for games. However, most of these existing solutions emphasize horizontal techniques, shifting between pre-rendered layers at runtime. There seems to be a small disconnect between the digital audio workspace (DAW) and the runtime API for adapting the music. Many vertical techniques suffer from this disconnect because pre-rendered audio does not provide that flexibility.

## Goal
In order to fix the lack of flexibility in the production of adaptive music, we will develop a comprehensive workflow including an API for game developers to utilize, a custom filetype for orchestrating various other files (MIDI, soundfonts, our object notation), a headless back-end that is an abstracted layer on top of the [Thread Safe Audio Library (TSAL)](https://github.com/Calvin-CS/TSAL) to talk to various clients using RPC, a DAW client for testing our clients, and a plugin for testing our workflow within existing game engines. 
