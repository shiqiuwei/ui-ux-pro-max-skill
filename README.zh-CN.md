# [UI UX Pro Max](https://uupm.cc)

<p align="center">
  <a href="https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/releases"><img src="https://img.shields.io/github/v/release/nextlevelbuilder/ui-ux-pro-max-skill?style=for-the-badge&color=blue" alt="GitHub Release"></a>
  <img src="https://img.shields.io/badge/推理规则-161-green?style=for-the-badge" alt="161 推理规则">
  <img src="https://img.shields.io/badge/UI风格-67-purple?style=for-the-badge" alt="67 UI 风格">
  <img src="https://img.shields.io/badge/python-3.x-yellow?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.x">
  <a href="https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/blob/main/LICENSE"><img src="https://img.shields.io/github/license/nextlevelbuilder/ui-ux-pro-max-skill?style=for-the-badge&color=green" alt="License"></a>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/uipro-cli"><img src="https://img.shields.io/npm/v/uipro-cli?style=flat-square&logo=npm&label=CLI" alt="npm"></a>
  <a href="https://www.npmjs.com/package/uipro-cli"><img src="https://img.shields.io/npm/dm/uipro-cli?style=flat-square&label=downloads" alt="npm 下载量"></a>
  <a href="https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/stargazers"><img src="https://img.shields.io/github/stars/nextlevelbuilder/ui-ux-pro-max-skill?style=flat-square&logo=github" alt="GitHub Stars"></a>
  <a href="https://paypal.me/uiuxpromax"><img src="https://img.shields.io/badge/PayPal-支持开发-00457C?style=flat-square&logo=paypal&logoColor=white" alt="PayPal"></a>
</p>

> 🌐 [English](README.md) | 中文

一款 AI 技能，为多平台和框架提供专业 UI/UX 设计智能。

<p align="center">
  <a href="https://uupm.cc">
    <img src="screenshots/website.png" alt="UI UX Pro Max" width="800">
  </a>
</p>

<p align="center">
  <b>如果你觉得这个项目有用，请考虑支持：</b><br><br>
  <a href="https://paypal.me/uiuxpromax"><img src="https://img.shields.io/badge/PayPal-捐助-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal 捐助"></a>
</p>

<p align="center">
  <i>其他项目</i><br>
  <a href="https://nextlevelbuilder.io">NextLevelBuilder.io</a> | <a href="https://goclaw.sh">GoClaw.sh</a> | <a href="https://claudekit.cc">ClaudeKit.cc</a> | <a href="https://tose.sh">TOSE.sh</a>
</p>

## v2.0 新特性

### 智能设计系统生成

v2.0 的旗舰功能是 **设计系统生成器** —— 一个 AI 驱动的推理引擎，能在几秒内分析你的项目需求并生成完整、定制化的设计系统。

```
+----------------------------------------------------------------------------------------+
|  目标：Serenity Spa - 推荐设计系统                                                       |
+----------------------------------------------------------------------------------------+
|                                                                                        |
|  页面结构：Hero 主图 + 社会证明                                                           |
|     转化策略：情感驱动 + 信任元素                                                         |
|     CTA：首屏展示，在评价区后重复                                                         |
|     页面分区：                                                                           |
|       1. Hero 主图                                                                      |
|       2. 服务展示                                                                        |
|       3. 用户评价                                                                        |
|       4. 预约                                                                            |
|       5. 联系方式                                                                        |
|                                                                                        |
|  风格：柔软 UI 进化                                                                       |
|     关键词：柔和阴影、微妙层次、宁静感、高级质感、有机形状                                      |
|     适合：健康/美容/生活方式品牌、高端服务                                                   |
|     性能：优秀 | 无障碍：WCAG AA                                                           |
|                                                                                        |
|  配色：                                                                                  |
|     主色：    #E8B4B8（柔粉色）                                                           |
|     副色：    #A8D5BA（鼠尾草绿）                                                         |
|     CTA：     #D4AF37（金色）                                                            |
|     背景色：  #FFF5F5（暖白色）                                                           |
|     文字色：  #2D3436（炭灰色）                                                           |
|     备注：宁静调色板搭配金色点缀，营造奢华感                                                  |
|                                                                                        |
|  字体：Cormorant Garamond / Montserrat                                                  |
|     风格：优雅、宁静、精致                                                                 |
|     适合：奢侈品牌、健康美容、高端编辑风                                                     |
|     Google Fonts: https://fonts.google.com/share?selection.family=...                  |
|                                                                                        |
|  关键效果：                                                                               |
|     柔和阴影 + 流畅过渡（200-300ms）+ 温柔悬停状态                                          |
|                                                                                        |
|  避免（反模式）：                                                                          |
|     霓虹色 + 强烈动效 + 深色模式 + AI 紫粉渐变                                              |
|                                                                                        |
|  交付前检查清单：                                                                          |
|     [ ] 禁用 emoji 作图标（使用 SVG：Heroicons/Lucide）                                    |
|     [ ] 所有可点击元素加 cursor-pointer                                                    |
|     [ ] 悬停状态平滑过渡（150-300ms）                                                      |
|     [ ] 浅色模式：文字对比度最低 4.5:1                                                      |
|     [ ] 键盘导航焦点状态可见                                                               |
|     [ ] 支持 prefers-reduced-motion                                                     |
|     [ ] 响应式：375px、768px、1024px、1440px                                              |
|                                                                                        |
+----------------------------------------------------------------------------------------+
```

### 设计系统生成原理

```
┌─────────────────────────────────────────────────────────────────┐
│  1. 用户请求                                                      │
│     "为我的美容 SPA 构建落地页"                                    │
└─────────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────────┐
│  2. 多领域搜索（5 路并行）                                          │
│     • 产品类型匹配（161 个类别）                                   │
│     • 风格推荐（67 种风格）                                        │
│     • 配色方案选择（161 套）                                       │
│     • 落地页结构模式（24 种）                                      │
│     • 字体搭配（57 套组合）                                        │
└─────────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────────┐
│  3. 推理引擎                                                      │
│     • 产品 → UI 类别规则匹配                                      │
│     • 风格优先级（BM25 排序）                                     │
│     • 行业反模式过滤                                              │
│     • 决策规则处理（JSON 条件）                                    │
└─────────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────────┐
│  4. 完整设计系统输出                                               │
│     页面结构 + 风格 + 配色 + 字体 + 特效                           │
│     + 避免的反模式 + 交付前检查清单                                 │
└─────────────────────────────────────────────────────────────────┘
```

### 161 条行业专属推理规则

推理引擎涵盖以下专属规则：

| 类别 | 示例 |
|------|------|
| **科技 & SaaS** | SaaS、Micro SaaS、B2B 服务、开发工具/IDE、AI/聊天机器人平台、网络安全平台 |
| **金融** | 金融科技/加密货币、银行、保险、个人财务跟踪器、发票和账单工具 |
| **医疗健康** | 医疗诊所、药店、牙科、兽医、心理健康、用药提醒 |
| **电商** | 综合、奢侈品、P2P 市集、订阅盒、外卖 |
| **服务业** | 美容/SPA、餐厅、酒店、法律、家居服务、预约系统 |
| **创意** | 作品集、代理公司、摄影、游戏、音乐流媒体、图片/视频编辑 |
| **生活方式** | 习惯追踪、食谱烹饪、冥想、天气、日记、情绪追踪 |
| **新兴科技** | Web3/NFT、空间计算、量子计算、自主无人机 |

每条规则包含：
- **推荐页面结构** - 落地页布局方案
- **风格优先级** - 最匹配的 UI 风格
- **配色情绪** - 适合行业的调色板
- **字体情绪** - 字体个性匹配
- **关键效果** - 动效与交互
- **反模式** - 不应该做的事（例如银行业"禁用 AI 紫粉渐变"）

## 功能特性

- **67 种 UI 风格** - 玻璃拟态、黏土拟态、极简主义、野蛮主义、新拟物、Bento 网格、深色模式、AI 原生 UI 等
- **161 套配色方案** - 与 161 种产品类型一一对应的行业专属调色板
- **57 套字体搭配** - 精选字体组合，含 Google Fonts 导入链接
- **25 种图表类型** - 仪表盘和数据分析场景的图表推荐
- **15 个技术栈** - React、Next.js、Astro、Vue、Nuxt.js、Nuxt UI、Svelte、SwiftUI、React Native、Flutter、HTML+Tailwind、shadcn/ui、Jetpack Compose、Angular、Laravel
- **99 条 UX 指南** - 最佳实践、反模式和无障碍规则
- **161 条推理规则** - 行业专属设计系统生成（v2.0 新增）

### 可用风格（67 种）

<details>
<summary><b>通用风格（49 种）</b></summary>

| # | 风格 | 最适用场景 |
|---|------|-----------|
| 1 | 极简主义 & 瑞士风格 | 企业应用、仪表盘、文档 |
| 2 | 新拟物风格 | 健康/健身应用、冥想平台 |
| 3 | 玻璃拟态 | 现代 SaaS、金融仪表盘 |
| 4 | 野蛮主义 | 设计作品集、艺术项目 |
| 5 | 3D 与超现实主义 | 游戏、产品展示、沉浸式体验 |
| 6 | 鲜艳块状风格 | 初创公司、创意机构、游戏 |
| 7 | 深色模式（OLED）| 夜间模式应用、编程平台 |
| 8 | 无障碍 & 伦理设计 | 政府、医疗、教育 |
| 9 | 黏土拟态 | 教育应用、儿童应用、SaaS |
| 10 | 极光 UI | 现代 SaaS、创意机构 |
| 11 | 复古未来主义 | 游戏、娱乐、音乐平台 |
| 12 | 扁平化设计 | Web 应用、移动应用、初创 MVP |
| 13 | 拟物化设计 | 旧版应用、游戏、高端产品 |
| 14 | 液态玻璃 | 高端 SaaS、高档电商 |
| 15 | 动效驱动 | 作品集、故事叙述平台 |
| 16 | 微交互 | 移动应用、触屏 UI |
| 17 | 包容性设计 | 公共服务、教育、医疗 |
| 18 | 零界面 | 语音助手、AI 平台 |
| 19 | 柔软 UI 进化 | 现代企业应用、SaaS |
| 20 | 新野蛮主义 | Z 世代品牌、初创公司、Figma 风格 |
| 21 | Bento Box 网格 | 仪表盘、产品页、作品集 |
| 22 | Y2K 美学 | 时尚品牌、音乐、Z 世代 |
| 23 | 赛博朋克 UI | 游戏、科技产品、加密应用 |
| 24 | 有机仿生设计 | 健康应用、可持续品牌 |
| 25 | AI 原生 UI | AI 产品、聊天机器人、Copilot |
| 26 | 孟菲斯设计 | 创意机构、音乐、年轻品牌 |
| 27 | 蒸汽波 | 音乐平台、游戏、作品集 |
| 28 | 立体层叠 | 仪表盘、卡片布局、模态框 |
| 29 | 夸张极简 | 时尚、建筑、作品集 |
| 30 | 动态排版 | Hero 区块、营销网站 |
| 31 | 视差叙事 | 品牌故事、产品发布 |
| 32 | 瑞士现代主义 2.0 | 企业网站、建筑、编辑出版 |
| 33 | HUD / 科幻 FUI | 科幻游戏、航天科技、网络安全 |
| 34 | 像素艺术 | 独立游戏、复古工具、创意 |
| 35 | Bento 网格 | 产品特性、仪表盘、个人 |
| 36 | 空间 UI（VisionOS）| 空间计算应用、VR/AR |
| 37 | E-ink / 纸质感 | 阅读应用、数字报纸 |
| 38 | Z 世代混沌 / 极繁主义 | Z 世代生活、音乐艺术家 |
| 39 | 仿生 / 有机 2.0 | 可持续科技、生物科技、健康 |
| 40 | 反抛光 / 原生美学 | 创意作品集、艺术家网站 |
| 41 | 触感数字 / 可形变 UI | 现代移动应用、玩味品牌 |
| 42 | 自然精华 | 健康品牌、可持续产品 |
| 43 | 交互光标设计 | 创意作品集、互动体验 |
| 44 | 语音优先多模态 | 语音助手、无障碍应用 |
| 45 | 3D 产品预览 | 电商、家具、时尚 |
| 46 | 渐变网格 / 进化极光 | Hero 区块、背景、创意 |
| 47 | 编辑网格 / 杂志风 | 新闻网站、博客、杂志 |
| 48 | 色差 / RGB 分裂 | 音乐平台、游戏、科技 |
| 49 | 复古胶片 / 模拟风 | 摄影、音乐/黑胶品牌 |

</details>

<details>
<summary><b>落地页风格（8 种）</b></summary>

| # | 风格 | 最适用场景 |
|---|------|-----------|
| 1 | Hero 中心设计 | 视觉形象强烈的产品 |
| 2 | 转化优化型 | 线索收集、销售页面 |
| 3 | 功能丰富展示 | SaaS、复杂产品 |
| 4 | 极简直接型 | 简单产品、应用 |
| 5 | 社会证明聚焦 | 服务、B2C 产品 |
| 6 | 互动产品演示 | 软件、工具 |
| 7 | 信任与权威型 | B2B、企业、咨询 |
| 8 | 故事叙述型 | 品牌、机构、非营利 |

</details>

<details>
<summary><b>BI/数据分析仪表盘风格（10 种）</b></summary>

| # | 风格 | 最适用场景 |
|---|------|-----------|
| 1 | 数据密集仪表盘 | 复杂数据分析 |
| 2 | 热力图风格 | 地理/行为数据 |
| 3 | 高管仪表盘 | C 级别摘要 |
| 4 | 实时监控 | 运营、DevOps |
| 5 | 下钻分析 | 详细探索 |
| 6 | 对比分析仪表盘 | 并排比较 |
| 7 | 预测分析 | 预测、ML 洞察 |
| 8 | 用户行为分析 | UX 研究、产品分析 |
| 9 | 财务仪表盘 | 金融、会计 |
| 10 | 销售智能仪表盘 | 销售团队、CRM |

</details>

## 安装

### 使用 Claude Marketplace（Claude Code）

在 Claude Code 中用两条命令直接安装：

```
/plugin marketplace add nextlevelbuilder/ui-ux-pro-max-skill
/plugin install ui-ux-pro-max@ui-ux-pro-max-skill
```

### 使用 CLI（推荐）

```bash
# 全局安装 CLI
npm install -g uipro-cli

# 进入你的项目目录
cd /path/to/your/project

# 为你的 AI 助手安装
uipro init --ai claude      # Claude Code
uipro init --ai cursor      # Cursor
uipro init --ai windsurf    # Windsurf
uipro init --ai antigravity # Antigravity
uipro init --ai copilot     # GitHub Copilot
uipro init --ai kiro        # Kiro
uipro init --ai codex       # Codex CLI
uipro init --ai qoder       # Qoder
uipro init --ai roocode     # Roo Code
uipro init --ai gemini      # Gemini CLI
uipro init --ai trae        # Trae
uipro init --ai opencode    # OpenCode
uipro init --ai continue    # Continue
uipro init --ai codebuddy   # CodeBuddy
uipro init --ai droid       # Droid (Factory)
uipro init --ai kilocode    # KiloCode
uipro init --ai warp        # Warp
uipro init --ai augment     # Augment
uipro init --ai all         # 所有 AI 助手
```

### 全局安装（对所有项目可用）

```bash
uipro init --ai claude --global   # 安装到 ~/.claude/skills/
uipro init --ai cursor --global   # 安装到 ~/.cursor/skills/
```

### 其他 CLI 命令

```bash
uipro versions              # 列出可用版本
uipro update                # 更新到最新版本
uipro init --offline        # 跳过 GitHub 下载，使用内置资源
uipro uninstall             # 删除技能（自动检测平台）
uipro uninstall --ai claude # 删除特定平台
uipro uninstall --global    # 从全局安装中删除
```

## 前置条件

需要 Python 3.x 来运行搜索脚本。

```bash
# 检查 Python 是否已安装
python3 --version

# macOS
brew install python3

# Ubuntu/Debian
sudo apt update && sudo apt install python3

# Windows
winget install Python.Python.3.12
```

## 使用方法

### 技能模式（自动激活）

**支持：** Claude Code、Cursor、Windsurf、Antigravity、Codex CLI、Continue、Gemini CLI、OpenCode、Qoder、CodeBuddy、Droid (Factory)、KiloCode、Warp、Augment

技能会在你请求 UI/UX 工作时自动激活。只需自然对话：

```
为我的 SaaS 产品构建落地页
```

> **Trae**：请先切换到 **SOLO** 模式，技能将对 UI/UX 请求自动激活。

### 工作流模式（斜杠命令）

**支持：** Kiro、GitHub Copilot、Roo Code、KiloCode

使用斜杠命令调用技能：

```
/ui-ux-pro-max 为我的 SaaS 产品构建落地页
```

### 示例提示词

```
为我的 SaaS 产品构建落地页

为医疗分析创建仪表盘

设计一个带深色模式的作品集网站

制作一个电商移动应用 UI

构建带深色主题的金融科技银行应用
```

### 工作原理

1. **你提问** - 请求任何 UI/UX 任务（构建、设计、创建、实现、审查、修复、改进）
2. **生成设计系统** - AI 自动使用推理引擎生成完整设计系统
3. **智能推荐** - 根据你的产品类型和需求，找到最匹配的风格、配色和字体
4. **代码生成** - 以正确的颜色、字体、间距和最佳实践实现 UI
5. **交付前检查** - 针对常见 UI/UX 反模式进行验证

### 支持的技术栈

该技能为以下技术栈提供专属指南：

| 类别 | 技术栈 |
|------|--------|
| **Web（HTML）** | HTML + Tailwind（默认）|
| **React 生态** | React、Next.js、shadcn/ui |
| **Vue 生态** | Vue、Nuxt.js、Nuxt UI |
| **Angular** | Angular |
| **PHP** | Laravel（Blade、Livewire、Inertia.js）|
| **其他 Web** | Svelte、Astro |
| **iOS** | SwiftUI |
| **Android** | Jetpack Compose |
| **跨平台** | React Native、Flutter |

在提示词中说明你偏好的技术栈，或默认使用 HTML + Tailwind。

## 设计系统命令（进阶）

直接访问设计系统生成器：

> 注意：如果你通过 Continue 安装，请将下方命令中的 `.claude/skills/` 替换为 `.continue/skills/`。Droid (Factory) 用户请使用 `.factory/skills/`。

```bash
# 生成 ASCII 格式设计系统
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "beauty spa wellness" --design-system -p "Serenity Spa"

# 生成 Markdown 格式
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "fintech banking" --design-system -f markdown

# 按领域搜索
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "glassmorphism" --domain style
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "elegant serif" --domain typography
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "dashboard" --domain chart

# 按技术栈搜索
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "form validation" --stack react
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "responsive layout" --stack html-tailwind
```

### 持久化设计系统（主文件 + 覆盖模式）

将设计系统保存到文件，实现**跨会话的分层检索**：

```bash
# 生成并持久化到 design-system/MASTER.md
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "SaaS dashboard" --design-system --persist -p "MyApp"

# 同时创建页面专属覆盖文件
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "SaaS dashboard" --design-system --persist -p "MyApp" --page "dashboard"
```

这将创建 `design-system/` 目录结构：

```
design-system/
├── MASTER.md           # 全局来源（颜色、字体、间距、组件）
└── pages/
    └── dashboard.md    # 页面专属覆盖（仅与 Master 不同的部分）
```

**分层检索工作方式：**
1. 构建特定页面时（如"Checkout"），先检查 `design-system/pages/checkout.md`
2. 若页面文件存在，其规则**覆盖** Master 文件
3. 若不存在，则单独使用 `design-system/MASTER.md`

**上下文感知检索提示词：**
```
我正在构建 [页面名称] 页面。请阅读 design-system/MASTER.md。
同时检查 design-system/pages/[page-name].md 是否存在。
如果页面文件存在，优先使用其规则。
如果不存在，则单独使用 Master 规则。
现在生成代码...
```

## 架构 & 贡献

### 面向用户

代码库已重构为**基于模板的生成系统**。所有平台专属文件（`.cursor/`、`.windsurf/`、`.kiro/`、`.factory/` 等）现在由 CLI 动态生成。

**请始终使用 CLI 安装：**

```bash
npm install -g uipro-cli
uipro init --ai <platform>
```

这确保你获得最新模板和正确的 AI 助手文件结构。

### 面向贡献者

如果你想为本项目贡献：

```bash
# 1. 克隆仓库
git clone https://github.com/nextlevelbuilder/ui-ux-pro-max-skill.git
cd ui-ux-pro-max-skill

# 2. 了解项目结构
src/ui-ux-pro-max/           # 数据来源（数据、脚本、模板）
cli/                         # CLI 安装器（从模板生成文件）
.claude/                     # Claude Code 技能本地开发/测试
.factory/                    # Droid (Factory) 技能本地开发/测试

# 3. 在 src/ui-ux-pro-max/ 中进行修改
# - data/*.csv              → 数据库文件
# - scripts/*.py            → 搜索引擎 & 设计系统
# - templates/              → 平台专属模板

# 4. 同步到 CLI 并本地测试
cp -r src/ui-ux-pro-max/data/* cli/assets/data/
cp -r src/ui-ux-pro-max/scripts/* cli/assets/scripts/
cp -r src/ui-ux-pro-max/templates/* cli/assets/templates/

# 5. 构建并测试 CLI
cd cli && bun run build
node dist/index.js init --ai claude --offline  # 在临时目录中测试

# 6. 创建 PR（禁止直接推送到 main）
git checkout -b feat/your-feature
git commit -m "feat: description"
git push -u origin feat/your-feature
gh pr create
```

详细开发指南请参阅 [CLAUDE.md](CLAUDE.md)。

## Star 历史

[![Star History Chart](https://api.star-history.com/svg?repos=nextlevelbuilder/ui-ux-pro-max-skill&type=Date)](https://star-history.com/#nextlevelbuilder/ui-ux-pro-max-skill&Date)

## 许可证

本项目基于 [MIT 许可证](LICENSE) 授权。
