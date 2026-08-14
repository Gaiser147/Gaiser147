# Leonhard Hentschke

Embedded systems and edge AI. Starting my B.Sc. in Computer Science at the University of Potsdam in October 2026.

---

## What I work with

**Edge AI / Computer Vision:** YOLOv11, ONNX, HEF conversion, Raspberry Pi 5 + Hailo AI HAT, own datasets
**Embedded:** ESP32 / M5Stack, ev3dev, OpenWrt, compiling drivers and untangling toolchains
**Linux & Systems:** Arch, Nobara (Hyprland), self-hosted servers, networking
**RF / Mesh:** self-built Meshtastic and LoRa nodes
**Languages:** Python, JavaScript, Bash; currently learning C through an ESP32 project

---

## Projects

**[ev3dev_butter-robot](https://github.com/Gaiser147/ev3dev_butter-robot)**
Real-time object detection on embedded hardware
Split architecture: a Raspberry Pi 5 with a Hailo AI HAT does the vision, a LEGO Mindstorms platform running ev3dev does the moving. I collected and annotated my own dataset, trained YOLOv11, and converted it through ONNX to HEF for the accelerator. Camera and accelerator drivers had to be compiled by hand, and a HAT firmware update broke the toolchain badly enough that the whole conversion pipeline needed rebuilding. Detection runs reliably; the grabbing mechanism never fully worked.

**[clawdbot-twinmind-split-kit](https://github.com/Gaiser147/clawdbot-twinmind-split-kit)**
Self-hosted AI agent
An agent running on a Linux server I administer myself: external API integrations, automated research and writing tasks, split between a conversational agent and a background worker. Later ported to an M5Stack microcontroller with voice control via Deepgram (pocket-sized terminal for the agent). Along the way I found that one integrated API was not serving the models it claimed to.

**[gambleandy-solana](https://github.com/Gaiser147/gambleandy-solana)**
Solana token with automated fee lottery
A Token-2022 contract that automatically distributes accumulated transaction fees to a randomly drawn wallet. JavaScript and the Solana CLI, running on testnet.

**Meshtastic / LoRa mesh**
Several radio nodes built, configured and deployed around my area for text communication without cell infrastructure. Learned about range behaviour, power budgets and how nodes fail over a long winter the hard way XD.

---

## Open source

**[linux-wallpaperengine](https://github.com/Almamu/linux-wallpaperengine)** 
(C++) improvements to render effect compatibility: transparent framebuffer initialisation, texture handling in render passes, and shader compatibility transformations for HLSL-style outputs.
My original pull request was large, so the maintainers asked me to split it. It shipped as five individually reviewable PRs: [#567](https://github.com/Almamu/linux-wallpaperengine/pull/567), [#568](https://github.com/Almamu/linux-wallpaperengine/pull/568), [#569](https://github.com/Almamu/linux-wallpaperengine/pull/569), [#570](https://github.com/Almamu/linux-wallpaperengine/pull/570), [#571](https://github.com/Almamu/linux-wallpaperengine/pull/571) all merged. ([my fork](https://github.com/Gaiser147/linux-wallpaperengine))

---

## Publication

**AI-2027 Paper Review and Optimized Forecast: An AI-Generated Audit, Methodology Critique, and Revised Forecast** 
(Zenodo, April 2026)
[doi.org/10.5281/zenodo.19419882](https://doi.org/10.5281/zenodo.19419882)
A prediction audit and methodology critique of the AI-2027 study with an independent revised forecast for 2026–2032. The interesting part was the engineering: the dossier was produced by an autonomous multi-agent pipeline I built for it.

---

## Also familiar with

Android internals (custom ROMs, bootloader and boot image work), reverse engineering unfamiliar systems, and self-hosting whatever I would otherwise pay for.

---

## Currently

- Learning **C** properly, through an ESP32 project, so I arrive at university with something usable rather than syntax knowledge
- Documenting older projects that never got a README | Hate docs :-( 
- Looking for a **working student position (Werkstudent) in embedded software or edge AI** around Berlin and Potsdam, starting October 2026
