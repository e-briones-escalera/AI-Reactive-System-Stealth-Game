# AI-Reactive-System-Stealth-Game

This is a stealth-based horror game prototype developed entirely in Unreal Engine 5 using Blueprints, focusing on immersive environmental audio and real-time audio feedback. This solo project explores AI used in videogames, how to program it, implement it, as well as using adaptive audio systems, and player-driven interaction for storytelling support.

> 🧠 Technical case study designed to explore AI for videogames, and to showcase my game developing, debugging, and QA awareness inside game engines abilities.

## AI System Highlights
- Custom AI that responds to **audio cues** and **player actions**.
- Footsteps, branches, and other world elements are mapped to generate **noise values**.
- The AI tracks noise over time and adjusts its behaviour (search, patrol, chase).

## Blueprint System Breakdown
Check the System Breakdown Document for more info.
- Modular Blueprint architecture for character logic, audio triggers, and AI states.
- Uses Unreal's **Enhanced Input System**.
- Game mechanics implemented entirely without C++.
  
> **⚠️ Disclaimer:** This project is part of my technical portfolio. Code, assets, and design are not licensed for reuse or distribution.

## Audio Systems
- Adaptive system based on player's actions and performance throughout the game.
- Fully reactive environmental sounds.
- Sound propagation simulation with Blueprint logic.

## QA & Debugging Approach
- Debug tools to visualize hearing zones and player-generated noise.
- Handled edge cases like dead silence, bait scenarios and interrupted paths.
- Logged AI state transitions to better understand its decision-making flow.

## Tech & Tools Used
- Unreal Engine 5
- Blueprints
- Pro Tools
- Wwise

## Media
> [Gameplay](https://www.9csound.com/game-audio)

## Extra Docs
If you want to learn more about how this project was made, here are some additional documents included in this repo.
- Bugs Checklist.
- Dev Diary: Behind the Build.
- System Breakdown (with diagrams).



## Contact
If you'd like to know more or are interested in how this system was built, feel free to reach out via [LinkedIn](www.linkedin.com/in/e-briones-escalera)
