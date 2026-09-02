# 旧 Phaser 原型隔离说明

本目录用于标记现有原型与目标独立游戏之间的边界，不会移动或删除用户已有文件。

## 现有历史资料

- 仓库根目录 `README.md`：混合描述已实现 Phaser MVP、旧讨论结论和长期设想。
- `src/`：当前 Phaser + TypeScript 原型实现。
- `assets/concepts/`：早期概念探索和未进入正式资产管线的参考图片。
- 当前 Git 分支 `feature/dark-survivor-mvp`：原型迭代历史。

## 隔离原则

- 旧资料保留作为体验验证、实现参考和历史记录，不直接删除或覆盖。
- 旧资料中的一项规则只有在新讨论中再次确认后，才进入目标游戏设计。
- 目标宏观设计维护在 `docs/design/TARGET_GAME_DESIGN.md`。
- 目标详细决策维护在 `docs/design/GAME_ARCHITECTURE.md`。
- 未来若建立新的独立 PC 项目或新 GitHub 仓库，应从目标设计重新搭建技术架构，而不是直接扩张当前单场景 Phaser 原型。
