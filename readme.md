#  CARS FOR SPEED // 100 OCTANE TUNER GARAGE

> A high-velocity, retro-arcade portfolio and OutRun-style 16-bit raster racer engine. Hand-rolled with **100% vanilla HTML5, CSS3, and JavaScript**  zero frameworks, zero external runtime bloat.

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)
[![Tech Stack](https://img.shields.io/badge/Stack-Vanilla_HTML_|_CSS_|_JS-yellow.svg)](#features)
[![Stage](https://img.shields.io/badge/Stage-1986_OutRun_Arcade-blue.svg)](#arcade-mini-game)

---

##  Live Demo
Experience the midnight dyno bay and race the retro highway live in your browser:  
 **[Launch Cars for Speed](https://dennispathe123.github.io/cars-for-speed/)**

 ---

 ##  Core Features

 ### 1.  ECU Diagnostic Boot Screen
 - Authentic retro BIOS terminal routine verifying fuel injection maps, sensor buses, and turbo spooling before wiping into the main console.
 - Real-time simulated progress telemetry bar with smooth CSS scale-exit animations.

 ### 2.  16-Bit Pseudo-3D *OutRun* Arcade Engine
 - **True Perspective Raster Scanlines:** Grounded 3D road rendering utilizing mathematical depth projection ($1 / Z$), avoiding flat-plane nausea.
 - **Dynamic Curves & Horizon Parallax:** Sweeping highway S-curves and a rolling skyline that counter-scrolls based on lateral steering tilt.
 - **Traffic AI & Hitbox Detection:** Depth-sorted incoming traffic waves that smoothly scale from the horizon without distortion blowups.
 - **Classic 45s Countdown:** OutRun-style checkpoint timer, live speed gauge (KM/H), and distance score tracker.

 ### 3.  Dyno Bay & Telemetry Dashboard
 - Animated tachometer pulsing against a 9,000 RPM redline with manifold boost telemetry (2.2 Bar / 100 RON).
 - Hand-crafted rear-view sports coupe sprite with reactive exhaust backfires and illuminated taillights.
 - Full retro CRT scanlines and radial vignette overlays.

 ### 4.  Hardware & Garage Fleet
 - **V.A.Y.U. WebOS:** A browser-native desktop operating system built without frameworks.
 - **29" Downhill Mountain Bike:** 21-speed mechanical cross-country rig with fork crown lockout.
 - **Arduino Micro-ECU:** Bare-silicon embedded C prototyping testbeds for PWM drivers and IR sensors.

 ---

 ##  Game Controls

 | Key | Action |
 | :--- | :--- |
 | **`W`** or **``** | Accelerate Throttle |
 | **`S`** or **``** | Brake / Decelerate |
 | **`A`** or **``** | Steer Left (with chassis roll) |
 | **`D`** or **``** | Steer Right (with chassis roll) |

 ---

 ##  Project Architecture

 ```text
 cars-for-speed/
  index.html       # Structural DOM, Dyno Bay, HUD, and Canvas Engine
   style.css        # CRT scanlines, 80s synthwave horizon, responsive panels
    README.md        # Technical documentation & project dossier