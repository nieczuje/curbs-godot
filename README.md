<div align="center">
<img src="readme-images/logo.png" width="150">

# Curbs (Krawężniki) — Godot rewrite

</div>

![Handwritten](https://img.shields.io/badge/provenance-handwritten-brightgreen)

*2022: original git history*

A full rewrite of [Curbs](https://github.com/nieczuje/curbs-gdevelop), the mobile street-ball minigame originally built in GDevelop, done from scratch in Godot. Built as a learning project to compare the two engines (this Godot build was never released).

> Co-developed with [Ravenyy](https://github.com/Ravenyy) — forked from [his original repo](https://github.com/Ravenyy/Godot-Curbs) to keep the real collaborative commit history intact.

## Demo

Screenshots and a gameplay video are in [curbs-gdevelop](https://github.com/nieczuje/curbs-gdevelop). This build looks and plays almost identically.

## Structure

```
project.godot   Godot 3 project file, starts at src/ShuffleLevels.tscn
curbs1.apk      Android build
src/            Scenes (.tscn)
scripts/        GDScript
assets/         Images
sounds/         Sound effects
fonts/          Luckiest Guy font and its Godot font resources
icons/          App icons
android/        Godot's Android build template (Gradle), used to export the APK
readme-images/  Logo for this README
```

## Usage

**Android:**
Download `curbs1.apk` from this repo and install it on your phone.

**Desktop:**
Requires Godot 3.x (not Godot 4). Open `project.godot` in Godot and press F5. Swipe with the mouse, since touch is emulated from it.

## Tech

Godot 3.x (not compatible with Godot 4), GDScript. 2D physics (`RigidBody2D`) for the ball, GLES2 renderer, exported to Android.

## Credits

- Original project: [Godot-Curbs](https://github.com/Ravenyy/Godot-Curbs) by [Ravenyy](https://github.com/Ravenyy), MIT License. This repo is a fork of it, with the original copyright notice kept in `LICENSE`.
- Game font: [Luckiest Guy](https://fonts.google.com/specimen/Luckiest+Guy), Apache License 2.0.
<!-- TODO: credit sounds -->

## License

MIT License — see [LICENSE](LICENSE).
