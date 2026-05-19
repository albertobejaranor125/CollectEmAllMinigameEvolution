# CollectEmAll: Minigame Evolution

A retro-style mini game built with C++ and SDL2 where the player collects coins, avoids losing lives, and beats the clock.

## 🕹️ Gameplay Overview

* Control your animated character using `W`, `A`, `S`, `D`.
* Press the correct letter shown on the screen (`W`, `A`, `S`, or `D`) to earn points.
* Collect coins scattered on the screen to increase your score.
* Beat the timer and reach **100 points** to win.
* Lose lives by pressing incorrect keys: lose all lives and it's Game Over.
* Unlock new **levels** with higher difficulty as your score increases.
* High Score is saved locally and shown in the HUD.

## 🛠️ Features

* ✅ Game states: Menu, Playing, Paused, Game Over, Victory
* ✅ Sprite animation with a spritesheet
* ✅ Dynamic difficulty system (Levels)
* ✅ Persistent high score (`score.txt`)
* ✅ Manual and procedural item collisions
* ✅ Background music and sound effects
* ✅ Smooth transitions and simple UI polish

## 🎮 Controls

| Action | Key |
|---|---|
| Move Up | W |
| Move Down | S |
| Move Left | A |
| Move Right | D |
| Pause / Resume Game | P |
| Back to Menu | ESC |

## 📦 Requirements

You need the following libraries installed (statically or via DLLs):
* [SDL2](https://www.libsdl.org/)
* [SDL2_image](https://github.com/libsdl-org/SDL_image)
* [SDL2_ttf](https://github.com/libsdl-org/SDL_ttf)
* [SDL2_mixer](https://github.com/libsdl-org/SDL_mixer)

## 🚀 How to Run

1. Clone the repository:
```bash
git clone [https://github.com/albertobejaranor125/CollectEmAllMinigameEvolution.git](https://github.com/albertobejaranor125/CollectEmAllMinigameEvolution.git)
```

2. Build the project in Release mode using Visual Studio (x86 or x64 as per configuration).

3. Make sure to copy all required .dll files and the assets/ folder next to the .exe.

4. Run the executable:
./CollectEmAllMinigameEvolution.exe
