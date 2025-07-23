# AI-Reactive-System-Stealth-Game

This is a stealth-based horror game prototype developed entirely in Unreal Engine 5 using Blueprints, focusing on immersive environmental audio and real-time audio feedback. This solo project explores AI used in videogames, how to program it, implement it, as well as using adaptive audio systems, and player-driven interaction for storytelling support.

> 🧠 Technical case study designed to explore AI for videogames, and to showcase my game developing, debugging, and QA awareness inside game engines abilities.

## AI System Highlights
- Custom AI that responds to **audio cues** and **player actions**.
- Footsteps, branches, and other world elements are mapped to generate **noise values**.
- The AI tracks noise over time and adjusts its behaviour (search, patrol, chase).

## Blueprint Systems Breakdown
- Modular Blueprint architecture for character logic, audio triggers, and AI states.
- Uses Unreal's **Enhanced Input System**.
- Game mechanics implemented entirely without C++.

## Audio Systems
- Adaptive ambience based on player's proximity to zones.
- Fully reactive environmental sounds.
- Sound propagation simulation with Blueprint logic (no Wwise).

## Testing & QA Notes
- Integrated debug tools to visualize hearing zones and noise generation.
- Stress-tested edge cases: dead silence, baited movement, and interrupted pathing.
- Logged AI decision tree steps to refine its reactivity.

## Tech & Tools Used
- Unreal Engine 5
- Blueprints
- Pro Tools
- Wwise

## Media
> [Gameplay](https://www.9csound.com/game-audio)

## Repository Notes
This repository contains:
- Blueprint screenshots and documentation
- Debug tool demos
- Level design diagrams

> **⚠️ Disclaimer:** This project is part of my technical portfolio. Code, assets, and design are not licensed for reuse or distribution.

## Contact
If you'd like to know more or are interested in how this system was built, feel free to reach out via [LinkedIn](www.linkedin.com/in/e-briones-escalera).
