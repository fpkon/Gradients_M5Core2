# Gradients_M5Core2

## Gameplay
Control a red orb by tilting the M5Core2 device. The goal is to collect as many green orbs as possible within a limited time. The game starts with a 90-second timer, but each captured orb adds extra time. The score for each orb is inversely proportional to the time taken to collect it, with a minimum of 100 points per orb—so speed matters! Orbs spawn randomly on the screen.

The terrain is randomly generated, with red zones representing peaks and blue zones as valleys. Brute force won't always work—sometimes, the best approach is to build momentum by rocking back and forth. The playing area is bounded by the screen edges, which can be strategically used for tricky orb placements near the borders.

Your high score is saved in persistent memory.

## Further Work
I have a few ideas for expanding this project:
- **Gameplay Analysis** – Log playing data to analyze different playstyles.
- **Multiplayer Mode** – Remove the timer, set a fixed number of collectible orbs, and compete (or collide!) with other players to grab them.
- **Singleplayer vs. CPU** – Use collected gameplay data to train a bot opponent.
- **Sound Effects** – Add audio feedback for actions and events.
- **In-Game Modifiers** – Experiment with changes like altered gravity, increased pickup range, or spawning more orbs in valleys than on peaks.

Have fun! 🚀
