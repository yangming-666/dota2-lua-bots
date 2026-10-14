# Ranked Matchmaking AI — personal fork

A personal fork of the Lua bot scripts from [Ranked Matchmaking AI](https://github.com/adam3q/dota2ai). The bot code uses Valve's Dota 2 Bot Scripting API.

[中文安装指南](README_zh_CN.md) · [GPL-3.0 license](LICENSE) · [Contributing](CONTRIBUTING.md)

## Project scope

This repository contains hero ability/item logic, hero selection, farming, laning, pushing, roaming, and utility scripts. It is a Lua bot project, not a screen-only autonomous player.

The separate [Dota 2 External Vision AI](https://github.com/yangming-666/dota2-external-vision-ai) repository contains the Python vision research prototype. Historical local experiments under `external_vision_ai/` are not the supported entry point for that project.

## Getting started

Follow the existing [Chinese installation guide](README_zh_CN.md) for the Workshop and local bot-script workflows. Workshop links in that guide refer to the upstream project, not a release published by this fork.

For source inspection:

```sh
git clone https://github.com/yangming-666/dota2ai.git
cd dota2ai
```

| Area | Files |
|---|---|
| Hero behavior | `ability_item_usage_*.lua`, `bot_*.lua`, `hero/` |
| Strategy modes | `mode_*.lua`, `team_desires.lua` |
| Shared behavior | `utility.lua`, `util/`, `hero_selection.lua` |

## Maintenance status

Upstream game-patch compatibility is not guaranteed by the existence of this fork. Gameplay changes require testing in local bot matches with the target Dota 2 version. No new gameplay release is claimed by this documentation cleanup.

Preserve upstream attribution and GPL-3.0 terms when modifying or redistributing the Lua source.
