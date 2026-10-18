# ardot-mobile-app-multi-screen · Multi-Screen Mobile App Mockups

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Agent Skill](https://img.shields.io/badge/Agent%20Skill-SKILL.md-blue.svg)](SKILL.md)
[![Category](https://img.shields.io/badge/category-design-8a2be2.svg)](#)
[![Version](https://img.shields.io/badge/version-1.0.0-informational.svg)](#)
[![llms.txt](https://img.shields.io/badge/AI--friendly-llms.txt-101E2C.svg)](llms.txt)
[![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-README.md-blue.svg)](README.md)

> Produce many mobile app screens (home / list / detail / edit / third-party) on one Ardot canvas — unified iPhone size, status bar, bottom capsule tab bar and a single accent color, compared screen-by-screen against a fixed spec to avoid drift.

**Keywords**: Ardot 多屏 · 移动端 App · App 原型 · iPhone 尺寸稿 · 多屏统一风格 · UI 原型 · mobile app screens · mockup

This repository is an **Agent Skill distribution package**. The core file `SKILL.md` follows the Agent Skills spec (YAML frontmatter) and packages the method of "一次画一整套 App 页面，尺寸 / 间距 / 配色不漂移" into a skill an AI agent can load directly. Drop it into your agent's skills directory (e.g. `~/.workbuddy/skills/`).

- **Category**: 设计工具 / Design
- **Version**: 1.0.0
- **Author**: 诺声(Logos)@SynomosAI
- **License**: MIT (see [LICENSE](LICENSE))

---

## Features

- 一次出多屏：首页 / 列表 / 详情 / 编辑 / 第三方打通等成套产出
- 统一基底：iPhone 尺寸、状态栏、底部胶囊标签栏一致
- 单点缀色：全画布只用一个点缀色，控制视觉统一
- 逐屏规格比对：以既定设计规格为唯一参照，不逐屏自由发挥
- 防漂移：避免多屏之间尺寸 / 间距 / 配色各自漂移
- 多语种：中 / 英 / 日 / 韩 / 西 / 法 / 德 / 阿（核心 8 种）

---

## Quick Start

Prerequisite: an AI coding assistant / skill runtime that can load Agent Skills. 无独立可执行服务；本包为多屏设计规格方法论.

```bash
# 1. 克隆本仓库
git clone https://github.com/zhaoxinghua09-cell/ardot-mobile-app-multi-screen.git
cd ardot-mobile-app-multi-screen

# 2. 查看技能主文件（iPhone 尺寸规格、胶囊标签栏、单点缀色口径）
cat SKILL.md

# 3. 把技能目录放进你的 Agent 技能目录（示例：WorkBuddy）
#    cp -r . ~/.workbuddy/skills/ardot-mobile-app-multi-screen/
```

Then invoke it in natural language, e.g.:

```text
「怎么一次画一整套 App 页面」
「多屏风格怎么统一」
「按 iPhone 尺寸出一套移动端原型」
```

---

## Usage

1. Clone this repo, or copy the skill directory into your agent's skills folder.
2. Call the capability via the trigger keywords described in `SKILL.md`.
3. See `SKILL.md` for the full method, boundaries and provenance.

---

## Repository layout

```text
ardot-mobile-app-multi-screen/
├── README.md            # 本文件（双语）
├── README.en.md         # 英文版说明
├── SKILL.md             # 技能主文件（Agent Skills 规范 · YAML frontmatter）
├── manifest.json        # 技能元数据（名称 / 版本 / 许可 / 描述）
├── LICENSE              # MIT 许可全文
├── SECURITY.md          # 安全策略
├── CONTRIBUTING.md      # 贡献指南
├── AGENTS.md            # 给 AI Agent 的工作指引
├── llms.txt             # 给 AI 的最小索引（llms.txt 标准）
└── llms-full.txt        # 给 AI 的完整文本
```

---

## License

Released under the **MIT** license. See [LICENSE](LICENSE) for the full text. Attribution: cite this repository `https://github.com/zhaoxinghua09-cell/ardot-mobile-app-multi-screen` and the rights holder "赵兴华 / Steven Zhao·China". Contact: zhaoxinghua06@126.com ｜ ORCID 0009-0001-0512-1237.

---

## Security

If you find a security issue, report it privately per [SECURITY.md](SECURITY.md); do not disclose it in a public issue.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Keep the `SKILL.md` YAML frontmatter fields compatible when changing this skill.

## Disclaimer

This repository content is a **theoretical stance and tooling exploration**. It does not represent any certified, commercially delivered, or client-served claim. External standards, certifications and clause information are restatements of public sources; independently verify before formal citation. APIs, authorization codes and ambassadors are roadmap items, not yet live.
