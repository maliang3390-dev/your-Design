# your-Design

A design aesthetics distiller skill — covers all categories of visual design analysis and user experience flow analysis. Analyze styles across regions (US, Japan, China, Europe), industries (SaaS, e-commerce, brand sites, tools), and aesthetics (minimalist, dark mode, luxury, Japanese Wabi-sabi, etc.).

## Key Features

- **Visual design analysis** across 5 dimensions: Gestalt compliance, color system, typography, layout, and component style — each backed by practical UX frameworks and psychology principles
- **User journey analysis** across 6 dimensions: first-screen attention flow, core task conversion, navigation architecture, interaction feedback, drop-off points, and reusable experience patterns
- **Design-to-code gap analysis**: compare UI mockups against live demos, identify fidelity gaps, and get actionable fix suggestions
- **Pattern distillation**: accumulate samples in the same category to automatically extract reusable visual + experience patterns
- **Private library**: all samples and analyses are saved to your local `user/` directory, isolated from public kernel updates

## Installation

Place the skill folder under your skills directory:

```
~/.claude/skills/your-Design/
```

Or import the `.skill` package file if provided.

## Usage

| You say... | Skill does... |
|-----------|---------------|
| "Analyze this site and add it to my library" | Full 5-dim visual analysis + basic journey analysis → sample card saved |
| "Deep dive the conversion flow of X" | Full 6-dim journey breakdown → journey analysis card saved |
| "Summarize design patterns for SaaS websites" | Cross-reference all SaaS samples → distill reusable patterns |
| "Compare the design of X and Y" | Side-by-side dimension comparison table |
| "Design an X with Y style" | Visual style guide + journey architecture recommendations |
| "Check how closely this demo matches the mockup" | 6-item fidelity check + prioritized fix suggestions |
| Share a link in a design context | Proactively ask "Want me to collect and analyze this?" |

## Directory Structure

```
your-Design/
├── SKILL.md                    # Entry point: methodology + commands + module specs
├── references/
│   ├── frameworks.md           # 18 UX frameworks & psychology principles quick-reference
│   └── seeds-public.md         # 30 built-in benchmark samples (updated with kernel)
└── user/                       # Your private library (never overwritten by updates)
    ├── samples/                # Design sample cards
    ├── journeys/               # Deep journey analysis cards
    └── patterns/               # Distilled design patterns
```

## Data Isolation

- `SKILL.md` + `references/` are the **public kernel** — replaced on version updates
- `user/` is your **private library** — never touched by updates
- New kernel versions may add analysis dimensions; older sample cards missing new fields remain fully functional

## Built-in Benchmarks

30 pre-loaded samples across 3 categories:
- **10 SaaS & developer tools**: Linear, Stripe, Vercel, Raycast, Notion, Figma, Resend, Supabase, Webflow, Mural
- **10 Global brand sites**: Apple, Sony, Aesop, Hermes, Bang & Olufsen, Nike, Lexus, Muji, Tesla, IKEA
- **10 Japanese design benchmarks**: Nendo, NDC, ISSEY MIYAKE, Maruoka Castle, iro Inc., SHISEIDO, G-Mark, Kenji Saito, MUJI Japan, Lexus Japan

## License

MIT

--------------------------------------------------------------------

# your-Design 设计审美蒸馏器

覆盖全品类风格的视觉设计分析与用户体验动线分析 Skill。可分析不同地区（美国、日本、中国、欧洲）、不同品类（SaaS、电商、品牌站、工具）和不同风格（极简、暗色模式、奢侈风、日式侘寂等）的设计，并沉淀为可复用的设计规律。

## 核心能力

- **5 维视觉设计分析**：格式塔合规度、色彩系统、排版体系、布局特征、组件风格 — 每项依托实战 UX 框架与心理学原则
- **6 维体验动线分析**：首屏注意力动线、核心任务转化、导航信息架构、交互反馈、流失断点、可复用体验规律
- **设计落地差异校验**：对比 UI 设计稿与代码 Demo，识别还原度偏差，给出优先级修复建议
- **规律蒸馏**：同品类样本积累到一定数量后自动提炼通用的视觉 + 体验设计原则
- **私有库数据隔离**：所有样本和分析保存在本地 `user/` 目录，Skill 公版更新不会被覆盖

## 安装

将 Skill 文件夹放到你的 skills 目录下：

```
~/.claude/skills/your-Design/
```

或导入提供的 `.skill` 打包文件。

## 使用方式

| 你说… | Skill 会… |
|-------|----------|
| "帮我分析这个网站的设计并收录" | 5 维视觉分析 + 基础动线 → 样本卡片归档 |
| "深度拆解 XX 的转化动线" | 6 维权量动线分析 → 独立动线分析卡片 |
| "总结 SaaS 官网的通用设计规律" | 检索全部 SaaS 样本 → 蒸馏品类规律 |
| "对比 XX 和 XX 的设计差异" | 逐维对比表 |
| "参考 XX 风格设计一个 XX" | 视觉方案 + 动线架构建议 |
| "校验这个 UI 稿和 Demo 的还原度" | 6 项还原度检查 + 优先级修复建议 |
| 分享链接且语境涉及设计 | 主动问"是否收录并分析？" |

## 目录结构

```
your-Design/
├── SKILL.md                    # 入口：方法论 + 指令路由 + 模块执行细则
├── references/
│   ├── frameworks.md           # 18 个 UX 框架与心理学原则速查卡片
│   └── seeds-public.md         # 30 个公版内置标杆样本（随内核更新）
└── user/                       # 你的私有库（更新永不被覆盖）
    ├── samples/                # 设计样本卡片
    ├── journeys/               # 动线深度分析卡片
    └── patterns/               # 蒸馏出的设计规律
```

## 数据隔离

- `SKILL.md` + `references/` 为**公版内核**，版本更新时直接替换
- `user/` 为你的**私有数据库**，更新时完整保留
- 新版本方法论若新增分析维度，旧样本卡片缺失该字段不影响正常使用

## 内置标杆样本

30 个精选样本，覆盖 3 大类：
- **10 个 SaaS 与开发者工具**：Linear、Stripe、Vercel、Raycast、Notion、Figma、Resend、Supabase、Webflow、Mural
- **10 个全球品牌站**：Apple、Sony、Aesop、Hermès、Bang & Olufsen、Nike、Lexus、Muji、Tesla、IKEA
- **10 个日式设计标杆**：Nendo、NDC、ISSEY MIYAKE、丸岡城、iro Inc.、SHISEIDO、G-Mark、Kenji Saito、MUJI 日本版、Lexus 日本版

## 许可

MIT
