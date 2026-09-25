# Dodge 'Em: Overdrive

A playable prototype of a modern, single-input remake of Dodge 'Em. It's one self-contained `index.html` with procedural graphics and synthesized audio, and no build step.

**Play:** https://harshkaushik-atari.github.io/dodge-em-overdrive/

## How to play

- Your car drives itself counter-clockwise. Cyan crash cars drive the other way. You switch lanes at the glowing doors.
- **Chase camera (default):** a low 3D camera rides behind your car.
  - Tap the **left** side to move in (toward the middle) and the **right** side to move out.
  - **Hold** the middle to boost with Overdrive.
  - On phones there's also an IN / BOOST / OUT pad.
  - A minimap and **HEAD-ON!** warnings show what's coming.
- **Classic camera:** in Settings, turn off *Chase camera* (or press `C` between runs). This gives the top-down view, where you tap inside or outside your lane.
- Grab gold gems for points, and drive through power-up orbs: Shield, Magnet, Slow-mo, Double.
- Keyboard: `←`/`↓` in · `→`/`↑` out · `Space` hold to boost · `P` pause · `C` camera.
- 2 Players: P1 `↑` `↓` `Space` · P2 `W` `S` `Shift`.

## Modes

- **Endless:** starts easy and climbs Easy → Medium → Difficult → Hell. At every level-up, your car dives into a warp pipe, the camera orbits the new randomly shaped track, and it swoops back in behind you.
- **Daily:** Endless on a seed shared by everyone that day. Your best daily run races you as a ghost, and playing every day builds a streak bonus.
- **Levels:** 12 goals (gems, survive, clear every lane, dodges), each on a fresh random track that gets stranger in later levels.
- **2 Players:** local hunter vs. runner, with 60-second rounds and swapped roles. Desktop only, uses the classic view.

## Progression

- **Coins:** earn 1 per gem, plus a score bonus, mission rewards and a daily streak bonus. Spend them in the **Garage** on 8 unlockable car paints.
- **XP and ranks:** Rookie → Street → Racer → Pro → Ace → Elite → Champion → Legend → Mythic → Overdrive.
- **Missions:** three are always active, for example "collect 70 gems in one run" or "pull off 3 PASS dodges". Each pays out the moment you finish it, and a new one replaces it.

## Running locally

Open `index.html` in a browser. It needs no server. The only network request is for the Google Fonts it uses. The chase camera uses WebGL. Without WebGL the game falls back to the classic view.
