<p align="center">
  <img src="https://raw.githubusercontent.com/vaxicy/garden-letter-theme/main/assets/icon.png" alt="Garden Letter Theme logo" width="128">
</p>

<h1 align="center">Garden Letter Theme</h1>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=lilinhuang.garden-letter-theme"><img src="https://img.shields.io/badge/VS%20Code-Theme-71869B?logo=visual-studio-code" alt="VS Code Theme"></a>
  <img src="https://img.shields.io/badge/version-1.0.0-48515A?logo=visual-studio-code" alt="version 1.0.0">
  <img src="https://img.shields.io/badge/Variants-Light%20%26%20Dark-CEDABF?logo=visual-studio-code" alt="Light and Dark variants">
  <a href="https://github.com/vaxicy/garden-letter-theme/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Non--Commercial-lightgrey" alt="License: Non-Commercial"></a>
</p>

A letter written on garden paper for VS Code: **cream letter paper**, **muted slate-blue ink**, **sage leaves** and **pressed-flower lotus pink**. The light variant reads like a sunlit writing desk, the dark one like the same desk at dusk — both cut from one palette, so switching changes the light level rather than the character of the workspace.

一封信纸上的花园配色 VS Code 主题：**奶油信纸**的纸面、**灰蓝墨迹**的字迹、**鼠尾草绿**与**干花藕粉**的点缀。浅色版像日光下的书桌，深色版像同一张桌子的黄昏；两套变体共享同一套色板，切换时改变的是明暗而非气质。

## Preview / 预览

| Light 浅色 | Dark 深色 |
| --- | --- |
| ![Garden Letter Theme Light](https://raw.githubusercontent.com/vaxicy/garden-letter-theme/main/store-assets/screenshots/en/screenshot-light.png) | ![Garden Letter Theme Dark](https://raw.githubusercontent.com/vaxicy/garden-letter-theme/main/store-assets/screenshots/en/screenshot-dark.png) |

> Both previews are captured from a real VS Code window running the theme — no mockups.
>
> 上方预览图取自真实运行该主题的 VS Code 窗口截图，非模拟图。

## Palette / 色板

| Role | Light | Dark |
| --- | --- | --- |
| Editor background | `#FFFCF5` cream paper | `#2B3238` charcoal slate |
| Foreground | `#48515A` slate ink | `#E2E5DE` pale sage |
| Muted text / placeholders | `#7E8872` | `#8F9B7F` |
| Side bar | `#EEF1E8` with `#54604E` text | `#262D28` with `#C3CEBD` text |
| Panel / terminal | `#F5F3EA` | `#252D30` |
| Title bar | `#E9EDF1` with `#4D5968` text | `#22282D` with `#CAD2DA` text |
| Tab bar / inactive tab | `#ECEFE8` | `#222A2C` |
| Active tab indicator | `#B38D9F` | `#E1C1D0` |
| Activity bar | `#DEE5EA` with `#5D7288` icons | `#1E252A` with `#B8C3D3` icons |
| Status bar | `#DCE5D1` with `#536348` text | `#354331` with `#DCE7CF` text |
| Selection | `#DCE5D0` sage wash | `#4D6047` deep sage |
| Current line | `#FBF2DF` | `#343D3F` |
| Borders / indent guides | `#D8DFD4` / `#E5E7DD` | `#414D43` / `#404B42` |
| Button | `#CEDABF` with `#46553E` text (hover `#BFCEAD`) | `#CEDABF` with `#2D3C27` text (hover `#DFE8D2`) |
| Badge | `#71869B` with white text | `#B8C3D3` with `#2B3238` text |
| Cursor | `#71869B` | `#FDECCE` |
| Links | `#758C58` | `#CED8C2` |
| Errors / warnings | `#B05E65` / `#9C7B42` | `#E3A4AA` / `#E6CCA0` |
| Git added / modified / deleted | `#70895E` / `#A48657` / `#B3797E` | `#BCD2A8` / `#E0C59D` / `#DDA6AE` |

Brand palette: slate `#B8C3D3`, sage `#CEDABF`, lotus `#E1C1D0`, clay pink `#EFD1CD`, cream `#FDECCE`.

品牌色板：灰蓝 `#B8C3D3`、鼠尾草 `#CEDABF`、藕粉 `#E1C1D0`、陶粉 `#EFD1CD`、奶油 `#FDECCE`。

## Syntax mapping / 语法映射

| Syntax | Light | Dark |
| --- | --- | --- |
| Comments | `#929B87` italic | `#91A087` italic |
| Keywords / storage | `#986A83` pressed rose | `#E1C1D0` petal pink |
| Strings | `#647C51` sage | `#CEDABF` pale sage |
| Regexp | `#89A26A` | `#D1DBC5` |
| Escapes | `#9B7954` | `#E8C79B` |
| Numbers / constants | `#A07845` amber ink | `#FDECCE` cream |
| Types / classes / interfaces | `#847296` | `#D4C3DF` |
| Functions / methods | `#567792` slate blue | `#B8C3D3` pale slate |
| Properties | `#54817B` | `#B6D2C7` |
| Variables | `#48515A` | `#E2E5DE` |
| Parameters | `#81785D` | `#D4CDB5` |
| Operators | `#78816F` | `#BBC6B2` |
| Punctuation | `#91998A` | `#9FAE9B` |
| Tags | `#986A83` | `#EFD1CD` |
| Attributes | `#A07845` | `#FDECCE` |
| Headings / bold / italic | `#4D5C3A` | `#ECF0E6` |
| Invalid | `#B65353` | `#E99B91` |

Keywords stay pressed-flower rose, strings stay sage green and numbers stay amber and cream in both variants, so the syntax keeps its identity whichever variant you use.

关键字在浅色下是干花玫瑰粉、深色下是花瓣粉，字符串始终保持鼠尾草绿，数字始终保持琥珀与奶油色，两套变体的语法读感一致。

## Coverage / 覆盖范围

Every surface below is themed in both variants (144 UI colors each):

- **Editor** — background, foreground, selection and inactive selection, current-line highlight, word and selection highlights, find match and find highlight, bracket-match background and border, cursor, line numbers (plus the active line number), indent guides, whitespace, ruler, errors, warnings and info.
- **Workbench chrome** — activity bar, badge and active border, title bar (active and inactive), side bar with section headers and border, status bar (normal, no-folder and debugging states), editor group header and tabs (active, inactive, hover, modified border and active top border).
- **Panels and overlays** — panel, editor widgets, hover widget, suggest widget, dropdowns, inputs and placeholder text, notifications, quick input, and the focus border.
- **Lists** — active, inactive and hover selection backgrounds, plus the highlight and focus-highlight colors, and tree indent guides.
- **Terminal** — background, foreground and the full 16-color ANSI palette, matched to the theme.
- **Details** — workbench borders, scrollbar sliders, git decoration colors (added / modified / deleted) with their gutter markers, buttons, badges, diff editor backgrounds, and semantic token colors for variable, parameter, property, function, method, type, class and interface.

以下区域在两套变体中均已配色（每套 144 个 UI 颜色）：编辑器本体（选区与失焦选区、当前行、词/选区高亮、查找匹配与高亮、括号匹配、光标、行号、标尺、缩进线、空白符、错误/警告/提示）；活动栏与角标、标题栏、侧边栏（含分节标题）、状态栏（含无文件夹与调试态）、标签栏；面板与各类浮窗（悬停、建议、通知、快速输入）、下拉与输入框、列表选中/悬停/高亮、树缩进线；终端 ANSI 全色；全部边框与滚动条、Git 装饰色与 gutter 标记、按钮与角标、差异编辑器底色，以及变量/参数/属性/函数/方法/类型/类/接口的语义高亮。完整的颜色清单见 `COLOR-SPEC.md`。

## Features / 功能

- **Two coordinated variants** — `Garden Letter Theme Light` and `Garden Letter Theme Dark` ship in one extension.
- **One letter-paper palette** — cream and charcoal slate surfaces with slate-blue ink, sage green and pressed-flower pink accents.
- **Readable syntax colors** — pressed-rose keywords, sage strings, amber and cream numbers, tuned for contrast on both backgrounds.
- **Semantic highlighting** enabled, so language-aware tokens are colored beyond the classic TextMate scopes.
- **Terminal ANSI colors** taken from the same palette, so the integrated terminal sits inside the theme.

- **明暗两套协调变体**——同一扩展内含 `Garden Letter Theme Light` 与 `Garden Letter Theme Dark`。
- **一套信纸质色板**——奶油与炭灰石板底色，配灰蓝墨迹、鼠尾草绿与干花藕粉点缀。
- **可读的语法配色**——干花玫瑰粉关键字、鼠尾草绿字符串、琥珀与奶油色数字，在明暗底色上均保持对比。
- **启用语义高亮**，在传统 TextMate scope 之外为语言感知的 token 着色。
- **终端 ANSI 配色**取自同一色板，集成终端与主题融为一体。

## Installation / 安装

Requires VS Code 1.80 or newer.

1. Search for **Garden Letter Theme** in the Extensions view (`Ctrl+Shift+X` / `Cmd+Shift+X`), or open the [Marketplace page](https://marketplace.visualstudio.com/items?itemName=lilinhuang.garden-letter-theme).
2. Or install from a VSIX: download `garden-letter-theme-1.0.0.vsix`, open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`) and run **Extensions: Install from VSIX...**.

需要 VS Code 1.80 或更高版本。

1. 在扩展面板（`Ctrl+Shift+X` / `Cmd+Shift+X`）搜索 **Garden Letter Theme**，或打开 [Marketplace 页面](https://marketplace.visualstudio.com/items?itemName=lilinhuang.garden-letter-theme)。
2. 也可以从 VSIX 安装：下载 `garden-letter-theme-1.0.0.vsix`，打开命令面板（`Ctrl+Shift+P` / `Cmd+Shift+P`），运行 **Extensions: Install from VSIX...** 并选择该文件。

Or from the command line:

或使用命令行：

```
ext install lilinhuang.garden-letter-theme
```

## Activation / 启用

Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`), run **Preferences: Color Theme**, and choose **Garden Letter Theme Light** or **Garden Letter Theme Dark**.

To switch between the two variants quickly, use the keyboard shortcut `Ctrl+K Ctrl+T` at any time.

打开命令面板（`Ctrl+Shift+P` / `Cmd+Shift+P`），运行 **Preferences: Color Theme**，选择 **Garden Letter Theme Light** 或 **Garden Letter Theme Dark**。

随时可用快捷键 `Ctrl+K Ctrl+T` 在两套变体之间快速切换。

## Development / 开发

Open this folder in VS Code and press `F5` to launch an Extension Development Host with the theme loaded. Regenerate the real-window preview screenshots with:

在 VS Code 中打开本文件夹并按 `F5`，在扩展开发宿主中预览主题。重新生成真实窗口预览图：

```bash
python3 scripts/capture-real-screenshots.py
```

The script builds a throwaway VS Code profile, installs this theme into it, opens the sample project under `scripts/demo-project` and captures the window for both variants into `store-assets/screenshots/en/`.

脚本会临时创建一个独立的 VS Code 配置目录，把本主题装进去，打开 `scripts/demo-project` 示例工程，并把两套变体的窗口截图输出到 `store-assets/screenshots/en/`。

Check a build before publishing:

发布前自查：

```bash
python3 scripts/validate.py
```

It refreshes `COLOR-SPEC.md` from the theme JSON files, verifies that every color value is a valid hex code, checks that the screenshot edges match `titleBar.activeBackground`, and — when a `.vsix` is present — verifies the manifest publisher, version and theme entries.

脚本会依据主题 JSON 重新生成 `COLOR-SPEC.md`，校验所有颜色值均为合法十六进制，检查截图首行/首列与 `titleBar.activeBackground` 一致，并在存在 `.vsix` 时校验清单里的发布者、版本与主题条目。

Package the extension with:

打包扩展：

```bash
vsce package
```

## License / 许可

Released under the **Non-Commercial License** — licensed for personal, educational and non-commercial use. See [LICENSE](LICENSE) for details.

基于 **Non-Commercial License（非商业使用许可）** 发布，可用于个人、教育及非商业用途，详见 [LICENSE](LICENSE)。

## Feedback / 反馈

Found an unthemed area or want a tweak? Open an issue at [github.com/vaxicy/garden-letter-theme/issues](https://github.com/vaxicy/garden-letter-theme/issues).

发现没有配色的区域或想调整某处颜色，欢迎在 [GitHub Issues](https://github.com/vaxicy/garden-letter-theme/issues) 反馈。

## Publisher / 发布者

Published by **lilinhuang** on the Visual Studio Code Marketplace.

由 **lilinhuang** 发布于 Visual Studio Code Marketplace。
