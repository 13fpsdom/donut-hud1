# Donut HUD (Fabric)

A lightweight client-side HUD starter for Minecraft Java 1.21.11 / Fabric.

## Features
- Coordinates (X / Y / Z)
- Facing direction
- FPS
- Current dimension
- Dark translucent panel with purple accent

This HUD is client-side only. It does not automate gameplay or change server state.

## Build on GitHub (no local setup)
1. Put every file in this folder at the top level of a GitHub repository (including the hidden `.github` folder).
2. Open the **Actions** tab. The **build** workflow runs on every push, or press **Run workflow**.
3. When it is green, open the run and download the **donut-hud-jar** artifact. Unzip it to get `donut-hud-1.0.0.jar`.
4. Put that jar and Fabric API (for 1.21.11) into `.minecraft/mods`.

## Build locally
JDK 21, then `./gradlew build` (Windows: `gradlew.bat build`). The jar is `build/libs/donut-hud-1.0.0.jar` (ignore the `-sources` jar).

## Status
Not built or run by the author of these files. The Gradle wrapper (9.2.0), the hard-coded Loom version and the repository settings were adjusted to make the GitHub build work, but they are untested. If the build fails, send the error text.
