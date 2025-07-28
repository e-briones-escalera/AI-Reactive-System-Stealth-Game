## Dev Diary: Behind the Build
First I would like to thank you for reading this diary, I wanted to structure it like a blog, so it is easier to understand all of my notes and thoughts about this game. 

## Why did I create this game?
It all started when I was having a brainstorming session at night thinking how could I level up my career. I've always had the role of Technical Sound Designer in the games I've worked before, but I ended up thinking: **How could I go further?**  
We all know about AI by now, and how it is growing insanely fast in all industries, so I wanted to adapt and join the AI trend to have extra skills that could help me become a better professional in the gaming industry. At first I was afraid since back then 
I barely knew how to move myself around Unreal Engine, but I knew Unity and have worked with it before, so I thought: How hard can it be if I already know Unity? **Spoiler Alert: A LOT.**

## AI Challenges
Let’s start with the most interesting part, shall we? I knew Unreal Engine 5 had an AI system—but did I know how to use it? Absolutely not. I spent a lot of time learning how Blueprints, Behaviour Trees, Blackboards, and the Enhanced Input System worked. I built everything from scratch, so I had to learn it all: from Blend Spaces and Animation Blueprints to landscape tools that made my computer crash every time I opened the project.

But easily, the biggest challenge was making the enemy AI feel believable (and work, obviously). Debugging the detection logic and building states like chasing, investigating, patrolling, and attacking wasn’t the end of it—once the bear finally started moving, it looked completely unnatural. Its movement was stiff and floaty, until I realized I needed to go deeper into animation systems. That’s when I discovered the power (and fun) of Blend Spaces and state machines. The whole thing was overwhelming at first, but looking back, I learned a ton, and it did help the bear feel way more natural.

## Iteration and Playtesting
Playtesting taught me more than any tutorial ever could. I started noticing things I would’ve missed otherwise: the bear getting stuck on trees or in one state and not changing its behaviour, the player triggering chase states way too easily. Every session helped me refine mechanics, tweak sound triggers, and rebalance the enemy’s behaviour.

Some parts were frustrating—like realizing my entire AI system needed to be redone as it got too complex at one point that some states started to mess with one another, but each problem forced me to build better solutions. I learned to embrace iteration as part of the creative process, not just something you do at the end. And honestly, seeing the game slowly come together because of those tweaks was super rewarding.

## Personal Takeaways
This project taught me that shipping something,even if it's not perfect **yet**, is more valuable than waiting until everything feels "ready". I pushed myself out of my comfort zone technically and creatively, especially with things I used to avoid.

I also learned to work with limitations, both technical (like performance drops) and personal (time pressure or lack of experience in some systems). What surprised me the most was how much I actually enjoyed the problem-solving side of things. I realized that game development isn't about avoiding problems, it’s about being curious and persistent enough to solve them.

## Resources
Top 3 resources that helped me to figure this out and be able to create this project. I hope you find them useful! Please feel free to reach out if you have any question or just want to talk more about it.
- [Blueprints Visual Scripting (Epic Games Documentation)](https://dev.epicgames.com/documentation/en-us/unreal-engine/blueprints-visual-scripting-in-unreal-engine)
- [Blueprint Scripting (Coursera)](https://www.coursera.org/learn/blueprint-scripting)
- [Ryan Laley's Youtube Channel](https://www.youtube.com/@RyanLaley)

## Credits
Credits to [Blink](https://www.fab.com/sellers/Blink)! I bought their awesome stylized bear in FAB.
