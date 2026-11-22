# The Periodic Table of Gemini

![The Periodic Table of Gemini Cover](./assets/cover.png)

> **在线预览 (Live Demo)**：**[https://originjinmu.github.io/periodic-table-of-gemini/](https://originjinmu.github.io/periodic-table-of-gemini/)**  
> **完整数据文档**：[118 元素全整理 Markdown 文档](./periodic_table_of_gemini.md)

## 项目简介

**The Periodic Table of Gemini** 是对 Google Gemini 网页版隐藏彩蛋 **The Periodic Table of Gemini** 的完整致敬与交互式开源还原（长按或连续点击模型选择器触发）。页面以暗夜霓虹视觉呈现全部 **118 个化学元素**，高亮还原 **5 大 Gemini 彩蛋模型**（`H`、`C`、`Ne`、`Ar`、`K`）与截图原文中的 **50 Sn（Tin）** 条目，并提供中英双语切换、实时检索、类别筛选与长按彩蛋波浪动效。

---

## 5 大 Gemini 彩蛋模型（H / C / Ne / Ar / K）

| 序数 | 符号 | 元素 | 对应模型 / 彩蛋 | 定位与特点 |
| :---: | :---: | :--- | :--- | :--- |
| 1 | **H** | Hydrogen · 氢 | **Gemini 4 Hydrogen** | 快速日常主力与高频编码，约 165–170 tok/s，API `$1.50/$7.50` |
| 6 | **C** | Carbon · 碳 | **Gemini 4 Carbon** | 深度推理与长周期任务旗舰，标准价 `$4/$20`（11 月促销 `$2/$10`） |
| 10 | **Ne** | Neon · 氖 | **Gemini 4 Neon** | 复杂工程、代码智能体与科学工作中坚，约 110 tok/s，API `$3/$15` |
| 18 | **Ar** | Argon · 氩 | **Gemini 4 Argon** | Carbon 高效版，单轮消耗更低，标准价 `$4/$20`（11 月促销 `$2/$10`） |
| 19 | **K** | Potassium · 钾 | **Nano Banana** | 图像模型彩蛋，因香蕉富含钾元素而被藏在 K 的位置 |

> **官方截图原文保留**：**50 Sn（Tin · 锡）** 完整保留截图原文标签 `Bronze age - CuSn` 与英文介绍 `"Just 12% tin in copper launched the Bronze Age — Latin 'stannum' gives Sn."`；其余元素结合同样的一句话化学科普 / 词源彩蛋风格整理为中英双语。

---

## 功能亮点

- **完整 18 列标准周期表布局**：涵盖 1–118 号全部元素与镧系（57–71）、锕系（89–103）独立分组，支持悬浮即时预览与点击锁定详情。
- **5 大彩蛋模型主题联动**：点击 `H`、`C`、`Ne`、`Ar`、`K` 或顶部模型选择器即可切换对应模型配色光晕与规格卡片；**长按顶部模型选择器**可重现彩蛋波浪解锁动效。
- **中英双语 / 检索 / 筛选 / 主题切换**：支持 `双语` / `EN` / `中文` 实时切换、按序数/符号/中英文名称/科普内容即时搜索（快捷键 `/`）、10 大元素类别筛选与深/浅色主题切换。
- **零依赖纯前端单文件架构**：全量数据内置于 `index.html`，开箱即用，支持直接部署至 GitHub Pages。

---

## GitHub Pages 部署步骤

1. **Fork 或克隆本仓库** 到你的 GitHub 账号下。
2. 进入仓库页面，点击顶部的 **Settings（设置）** 选项卡。
3. 在左侧菜单中选择 **Pages**。
4. 在 **Build and deployment** 下的 **Source** 中选择 `Deploy from a branch`。
5. 在 **Branch** 下拉菜单中选择 `main` 分支及 `/ (root)` 目录，点击 **Save** 保存。
6. 等待 1–2 分钟部署完成后，即可通过 `https://<你的用户名>.github.io/periodic-table-of-gemini/` 访问。

---

## 作者与贡献者

| 头像 | 角色 | 名称 | 主页 / 联系 |
| :---: | :--- | :--- | :--- |
| — | **作者 (Author)** | **OriginJinMu** | [@OriginJinMu](https://github.com/OriginJinMu) |
| <img src="./assets/gemini-avatar.jpg" width="48" height="48" alt="Gemini Avatar" /> | **共同作者 (Co-author)** | **Gemini** | `gemini@google.com` |
