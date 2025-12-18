# Source Engine Movement for Roblox

A high-performance movement system for Roblox that emulates the classic physics of the Source Engine. This script replaces standard character physics with velocity-based movement, enabling advanced techniques like bunnyhopping and air strafing.

## Key Features

* **Momentum-Based Movement:** Implements classic acceleration and friction models.
* **Bunnyhopping (Bhop):** Allows bhop.
* **Air Strafing:** Precise control over mid-air trajectory using directional inputs.
* **Rocket Jumping:** Custom projectile mechanics that apply explosion-based knockback for vertical mobility.
* **Integrated Sound Engine:** Custom audio for footsteps, jumping, landing, and explosions.
* **Dynamic Ground Detection:** Uses raycasting for accurate state transitions (ground/air).
* **Control Interface:** On-screen GUI to toggle the movement system or safely destroy the script.

## Controls

| Key | Action |
| :--- | :--- |
| **Space (Hold)** | Continuous Bunnyhopping |
| **W, A, S, D** | Directional Movement & Air Strafing |
| **X** | Launch Rocket (for Rocket Jumping) |
| **ON/OFF Button** | Toggle the movement system |
| **DESTROY Button** | Reverts physics to default and removes the script |

## Installation (Execute)

To run the script in any executor, use the following code:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/Gorinch/Source-movement-in-roblox/refs/heads/main/Main.lua"))()
```
