# Times Tables Turbo 🏎️

A car-racing times tables game for kids — answer maths questions to race to the finish line and unlock new vehicles.

**Play it:** https://rwaldridge.github.io/times-tables-turbo/

**Test Trainer (school tests 1–12 in exact order):** https://rwaldridge.github.io/times-tables-turbo/tests/

---

## Test Trainer

`tests/index.html` is a separate version that runs the weekly school tests (1, 1a, 2, 2a … 12) with all 30 questions in the exact printed order. Answers are typed on a number pad (or picked from 4 choices). You race a ghost of your best time during the test, then earn turbo boosts (1 per 5 correct) for a Grand Prix mini-game: steer between lanes, dodge cones, grab stars and beat three rivals. Passing a test with 30/30 (the school pass mark) unlocks that test's car.

## How to play

1. Enter your name and pick which times tables to practise
2. Choose a difficulty (Easy = 180s, Medium = 60s, Hard = 45s)
3. Choose your operation: **Multiply**, **Divide**, or **Both**
4. Answer 20 questions correctly to finish the race
5. Complete the race to unlock a car in your garage — harder tables earn cooler cars!

## Features

- 🚗 **Car unlock system** — 12 vehicles from Wobbly Tuk-Tuk (×1) to Alien UFO Supreme (×12)
- ➗ **Division mode** — practise division alongside multiplication
- 🏁 **Victory lap** — confetti and a car zoom animation when you finish a race
- 🔥 **Streak bonuses** — keep a streak going for extra points
- 🏆 **High scores** — local leaderboard saved in the browser
- 🚗 **Garage** — track which cars you've unlocked across sessions

## Times tables & their cars

| Table | Car |
|-------|-----|
| ×1  | 🛺 Wobbly Tuk-Tuk |
| ×2  | 🚗 Learner Hatchback |
| ×10 | 🚙 Trusty 4x4 |
| ×5  | 🚕 Yellow Speedster |
| ×3  | 🚐 Turbo Van |
| ×4  | 🏎️ Formula Racer |
| ×6  | 🚓 Police Interceptor |
| ×9  | 🚒 Fire Fury |
| ×8  | 🚑 Turbo Medic |
| ×11 | 🛻 Thunder Pickup |
| ×7  | 🚀 Space Rocket |
| ×12 | 🛸 Alien UFO Supreme |

## Deployment

The game is a single self-contained HTML file with no dependencies. GitHub Pages serves it directly from the `main` branch root.

To enable GitHub Pages: **Settings → Pages → Source: Deploy from branch → main / (root)**.
