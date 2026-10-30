# CHANGELOG

## [Unreleased]

### 变更

- `apps/qtcloud-media` XDG 共享：CLI 按名称查 XDG 主题（paths.rs），studio 主题参数化并读同一份主题文件（theme.dart + paths_io.dart）；指针更新
- `apps/qtcloud-media` studio 单页工作台（Flutter Web + Linux 桌面：编辑 + 公众号排版预览 + 富文本复制，已装本机 ~/.local）；cli 发布 v0.1.1（crates.io + GH Release，skills 命令组随版上架）、studio 发布 v0.1.0（GitHub Release）；指针更新
- 学习人工改稿：CLI render 跳过开头 H1；新增 `qtcloud-media-wechat` 技能（src/cli/skills）与 `skills` 命令组（list/install，编译期内嵌）；brochure 正本同步人工改稿版并在 README 沉淀公众号稿件风格；指针更新
- `apps/qtcloud-media` 补 release-cli CI（cli/* tag → 三平台构建 + crates.io 发布，qtcloud-media-cli 0.1.0 已上架）；brochure 介绍文按反馈修订（cargo 安装、小标题统一、下一步改草稿质量评审）；指针更新
- 产品名统一为「媒体云」：仓根 README 的 QtCloud 子模块说明、toolkit 示例界面标题（旧称「新媒体云」「新媒体运营云」，领域名「量潮新媒体运营」不变）；指针更新
- 新增子模块 `data/brochure`（仓 quanttide-brochure-of-social-media），首篇：qtcloud-media-cli 介绍文章（公众号发布稿）
- `apps/qtcloud-media` 发布 cli/v0.1.0（GitHub Release，tag cli/v0.1.0）；指针更新
- `apps/qtcloud-media` CLI 排版改为逐元素全内联样式（去 `<style>` 块与 class，适配微信草稿箱清洗），publish 重新实测通过；指针更新
- `data/library` 排版器清单收录 WeMD；指针更新
- `apps/qtcloud-media` 初始化 `src/cli`（Rust：Markdown → 公众号排版 → 草稿箱直出，主题 TOML 驱动）与 `src/studio`（Flutter 骨架）；`publish` 已对真实公众号实测通过（草稿箱直出，不群发），指针更新
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
