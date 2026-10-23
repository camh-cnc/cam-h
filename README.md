# CAM-H

**Modern CNC control for Mach3 users moving to Grbl, grblHAL or FluidNC.**

CAM-H runs your CNC router from Windows with a real 3D view of your machine. Moving off Mach3? It reads your Mach3 profile, writes the settings to your new board, and prints a wiring sheet for moving the wires across.

**Status: free beta.** Expect gremlins, and please report them.

## Download

**[Download CAM-H for Windows](https://github.com/camh-cnc/cam-h/releases/latest/download/CAM-H-Setup.exe)** (Windows 10 / 11, 64-bit)

Windows will say "Windows protected your PC" because the installer isn't signed yet: click **More info**, then **Run anyway**.

## Free and licensed

- **Free, no key needed:** the full screen, the 3D simulator, loading and checking G-code, Mach3 profile import and the wiring sheet.
- **Licence key:** connecting a real machine. During the beta, testers get a free key: message the [CAM-H Facebook page](https://www.facebook.com/profile.php?id=61595646275820) with your board and machine size.

## Safety

CAM-H's E-STOP button is software. Your machine must have a **hardware E-stop that cuts power** to the motors and spindle, within reach every time it moves. In this beta: home first, keep rapids at 25% for the first runs, and air-cut new jobs before cutting material.

## What's on real boards in this beta

Running G-code files, feed hold / resume / stop / E-STOP, jogging, homing, zeroing (G54), Go To Zero, MDI, feed / spindle / rapid overrides, manual tool changes (M6), and writing Mach3 settings to the board.

Simulator-only for now: probing, tool setter, automatic tool changer, laser crosshair, warm-up, outline, surfacing, macros, plasma, the A axis, G55 to G59, and starting mid-program.

## Reporting a problem

Message the [Facebook page](https://www.facebook.com/profile.php?id=61595646275820) with what you did, what happened, a screenshot, your board (Diagnostics > Controller) and the CAM-H version (window title).

---

CAM-H is proprietary software. © 2026 Jay. All rights reserved. This repository holds the installers only, not the source code.
