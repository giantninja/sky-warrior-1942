# Sky Warrior 1942

A top-down arcade shooter that runs in the browser, built in a single day with Claude Opus as the coding agent.

**[Play it here](https://game1-iota-wheat.vercel.app/)** on desktop or mobile.

## About

Sky Warrior 1942 won first place and the $1,000 prize in a company-wide AI competition in January 2026. The challenge was to build a game using Claude Opus, and 29 games were submitted.

The gameplay is inspired by classic top-down arcade shooters such as 1942 and Galaga: you fly up the screen, dodge enemy fire, and shoot down waves of planes on the way to the boss.

## Features

- Waves of enemy planes, with minibosses and boss fights
- Three difficulty levels: Easy, Normal and Hard
- Power-ups: extra lives, shield, speed boost, repairs and bombs
- Health and shield bars, with a saved high score
- Music and sound effects
- Touch controls and a mobile layout, plus fullscreen mode

## Controls

| Action | Keys |
| --- | --- |
| Move | Arrow keys or WASD |
| Fire | Shift or Space |
| Drop a bomb | Z |
| Pause | P |
| Toggle music | M |
| Help | Esc |
| Restart after game over | Space |

On a phone or tablet, tap to start and use the on-screen controls.

## How it was built

- **One file, no dependencies.** The whole game is a single `index.html` of about 4,000 lines: HTML, CSS and plain JavaScript, with no framework, build step, or image and audio files.
- **Canvas and Web Audio.** Graphics are drawn in code on an HTML5 2D canvas, and sound comes from the Web Audio API.
- **Built with an AI agent.** Claude Opus wrote the code from my prompts. I directed the design, play-tested each change, and steered the fixes.
- **Git checkpoints.** I had not built a game with an agent before, so I committed after every working step. That gave me a known-good state to roll back to whenever a change made things worse. The 16 commits show the game evolving over the day, from a first working version to graphics, music, difficulty levels, a miniboss and mobile controls.

## Run it locally

Clone the repository and open `index.html` in a browser. Nothing needs installing.

```bash
git clone https://github.com/giantninja/sky-warrior-1942.git
cd sky-warrior-1942
open index.html
```

## Author

Steven Winner — [github.com/giantninja](https://github.com/giantninja) · [linkedin.com/in/steven-winner](https://www.linkedin.com/in/steven-winner)
