<p align="center">
  <img src="assets/banner.webp" alt="texup — a Claude Code skill for AI texture remastering" width="100%">
</p>

# texup-skill

Claude Code skill that drives [**texup**](https://github.com/veryCoolTimo/texture-auto-upscaler) — a local AI texture remaster tool for old games — conversationally. No terminal knowledge needed: install the skill and just say *"remaster the textures in my game."* Claude scans the game folder, shows you before/after comparison sheets, upscales with a quality preset, and applies into the game with backup and rollback — asking for your approval before anything touches the game.

## Install

```
/plugin marketplace add veryCoolTimo/texup-claude-skill
/plugin install texup-skill@texup
```

Then, in Claude Code: *"улучши текстуры в моей игре"* or *"upscale my game's textures"*.

The skill installs and runs the `texup` CLI for you (from the [texture-auto-upscaler](https://github.com/veryCoolTimo/texture-auto-upscaler) repo). Everything runs locally on your machine — Apple Silicon, NVIDIA, or CPU.

## What texup supports

Resident Evil 5 / 0 HD / 6 and other MT Framework games, Source engine (Half-Life 2, Portal, TF2), Bethesda (Skyrim, Fallout 4), id-Tech PK3/PK4 (Quake III, Doom 3), and any game with loose textures (PNG/JPG/TGA/BMP/DDS). See the [tool repo](https://github.com/veryCoolTimo/texture-auto-upscaler) for the full list.

## License

[MIT](LICENSE)
