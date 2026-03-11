# PolJ's Ship

PolJ's Ship is a React Native mobile game built with Expo Router.  
It is a space / sci-fi inspired tap game where the player controls a rocket, boosts upward, avoids crystal walls, and tries to survive as long as possible.

## Features

- Full-screen mobile gameplay
- Tap-to-boost rocket control
- Neon space / sci-fi theme
- Animated start screen
- Score tracking
- Best score tracking
- Game over and retry system
- Sound effects support
- Expo Router project structure

## Project Structure

```text
polj-birdy/
├── app/
│   ├── (tabs)/
│   │   ├── _layout.tsx
│   │   ├── about.tsx
│   │   ├── explore.tsx
│   │   └── index.tsx
│   ├── _layout.tsx
│   └── modal.tsx
├── assets/
│   ├── images/
│   └── sounds/
├── components/
├── constants/
├── hooks/
├── scripts/
├── app.json
├── eas.json
├── package.json
└── README.md

My game idea was a simple but fun mobile game called PolJ’s Ship. It is inspired by tap-based survival games where the player controls a character and tries to avoid obstacles for as long as possible. In my version, instead of a bird, I used a rocket in a neon space setting. The player only needs to tap the screen to make the rocket go up. If they do not tap at the right time, the rocket falls and crashes into the crystal walls or the ground. I wanted the game to feel easy to understand but still challenging to play. My goal was to make something that looks colorful, feels fast, and keeps the player wanting to try again to beat their best score.

The most difficult part to implement was the game logic, especially the movement and collision system. At first, it sounded simple: make the rocket move up when tapped, make it fall because of gravity, then add obstacles. But once I started coding it, I realized that small mistakes could make the whole game feel wrong. I had to balance the gravity, boost strength, wall speed, and gap size so the game would not be too hard or too easy. Collision detection was also tricky because I needed to make sure the game correctly knows when the rocket hits a wall, the ceiling, or the floor. Another hard part was making the game update smoothly while keeping the score, restart system, and screen animations working properly.

If I had more time, I would improve the game in many ways. First, I would add better sound effects and background music so the game feels more alive. I would also improve the rocket design by replacing emojis with custom images or sprites. Another thing I want to add is a main menu, settings, and maybe difficulty levels so the player can choose an easier or harder mode. I would also like to save the best score on the device so it stays even after closing the app. Lastly, I would improve the game over screen and add more visual effects like explosions, glowing walls, and smoother background animation. Overall, I am happy with the result because I was able to turn a simple idea into a playable game, but I also learned that even small games take a lot of testing, patience, and fixing.
