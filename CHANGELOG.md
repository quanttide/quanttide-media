# CHANGELOG

## [Unreleased]

### 变更

- `apps/qtcloud-media` 初始化 `src/cli`（Rust：Markdown → 公众号排版 → 草稿箱直出，主题 TOML 驱动）与 `src/studio`（Flutter 骨架），指针更新
- `data/library` 新增 `wechat/yanxu.md`：言序 YanXu（toolsvip.cn）精品调研（中文排版引擎 + 公众号草稿箱直出 + MCP 接入），并新建 `wechat/` 目录
- 实验室子模块改名：`examples/default` → `examples/quanttide-media-lab`（仓 quanttide-laboratory-of-social-media → quanttide-media-lab）


### Changed
- 重写 README：补全领域定义（概述、领域边界、子模块结构、许可 CC BY 4.0）
- 新增 LICENSE（CC BY 4.0）

## [0.1.0] - 2026-07-08

### Added
- 添加多个子模块：`apps/qtcloud-media`、`docs/archive`、`data/profile`、`data/archive`、`data/journal` 以及 `examples/default`。
- 在 `apps/`、`docs/`、`examples/` 等目录中添加 `.gitkeep` 占位文件。

### Changed
- 多次更新 `data/profile` 子模块的引用指针。
