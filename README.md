# Dodge 'Em: Overdrive

A playable prototype of a modern, single-input remake of Dodge 'Em. It's one self-contained `index.html` with procedural graphics and synthesized audio, and no build step.

**Play:** https://harshkaushik-atari.github.io/dodge-em-overdrive/

## How to play

- Your car (cream with a red stripe) drives itself counter-clockwise. Cyan crash cars drive the other way.
- Tap **inside** your lane to move in, or **outside** to move out. You switch lanes at the glowing doors.
- **Hold** to boost with Overdrive. On phones you can also use the IN / BOOST / OUT pad.
- Grab gold gems for points, and drive through power-up orbs: Shield, Magnet, Slow-mo, Double.
- Keyboard: `↓` in · `↑` out · `Space` hold to boost · `P` pause.
- 2 Players: P1 `↑` `↓` `Space` · P2 `W` `S` `Shift`.

## Modes

- **Endless:** starts easy and climbs Easy → Medium → Difficult → Hell. At every level-up your car dives into a warp pipe and pops out on a new, randomly shaped track. Shapes get stranger as you go: round, chamfered, squircle or diamond corners, often asymmetric.
- **Levels:** 12 goals (gems, survive, clear every lane, dodges), each on a fresh random track that gets stranger in later levels.
- **2 Players:** local hunter vs. runner, with 60-second rounds and swapped roles. Desktop only, since both players share one keyboard.

## Running locally

Open `index.html` in a browser. It needs no server. The only network request is for the Google Fonts it uses.
