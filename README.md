# DeckQuark

**QuarkDeck** 的发布仓库 —— 面向 Steam Deck（Decky Loader）的夸克网盘插件。

本仓库仅用于发布构建产物，插件源码与开发内容不在本仓库维护。请前往 [Releases](../../releases) 下载最新安装包。

## 功能

- **扫码登录**：首屏为独立扫码登录页，登录成功后才进入主界面；Cookie 仅保存在本机。
- **三个 Tab**：`文件`（目录浏览、多选、批量下载）/ `下载`（进度、取消、清理）/ `设置`（下载目录、并发数、同名策略、断点续传、登出）。
- 在「设置」中登出即回到扫码登录页。
- 支持触屏与手柄操作，适配 Steam Deck 游戏模式分辨率。

## 安装

1. 在 [Releases](../../releases) 下载 `QuarkDeck.zip`。
2. 在 Decky Loader 中从 ZIP 安装；或解压到 `~/homebrew/plugins/QuarkDeck`，然后重启 Decky Loader。

默认下载目录为 `~/Downloads`，可在插件「设置」中修改。

## Release 附件

| 文件 | 说明 |
| --- | --- |
| `QuarkDeck.zip` | Decky Loader 插件安装包（主产物） |
| `QuarkDeck-technical-design.md` | 夸克接口逆向、插件架构与 callable 契约 |
| `prototype.html` | 可交互原型（点击「模拟扫码成功」可体验完整门禁流程） |
