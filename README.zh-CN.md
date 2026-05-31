<div align="center">

<img src="https://raw.githubusercontent.com/gtskevin/repo-showcase/main/.github/assets/banner.svg" width="600" alt="Repo Showcase — 把你的 GitHub 仓库变成高颜值展示页" />

# ✨ Repo Showcase

### 让你的 AI Agent 成为 GitHub 增长黑客

**Codex / Claude Code Skill — 自动把任何仓库变成专业、吸睛的展示页面**

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-blue?logo=openai&logoColor=white)](https://github.com/gtskevin/repo-showcase#快速开始)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/gtskevin/repo-showcase/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/gtskevin/repo-showcase?style=social&logo=github)](https://github.com/gtskevin/repo-showcase/stargazers)

<p>
  <a href="README.md">🇺🇸 English</a> · <a href="README.zh-CN.md">🇨🇳 简体中文</a>
</p>

</div>

---

## 🔥 效果对比：Before → After

<table>
<tr>
<td width="50%" valign="top">

### ❌ 之前（Agent 默认输出）
```
# my-tool
一个数据处理工具。
## 安装
npm install my-tool
## 使用
import { process } from 'my-tool'
process(data)
## 许可证
MIT
```

*平平无奇，没有视觉吸引力，没有徽章，没有社会证明。访客 3 秒内离开。*

</td>
<td width="50%" valign="top">

### ✅ 之后（使用 repo-showcase）

`# ✨ my-tool`
*零配置，10 倍速数据处理*

`[![npm](badge)](link) [![stars](badge)](link) [![coverage](badge)](link)`

**🚀 亮点** · **⚡ 30 秒快速开始** · **📊 对比表** · **🎬 在线演示** · **❓ FAQ** · **⭐ Star History**

*专业、转化率优化、有社会证明和清晰价值主张。访客停留、浏览、点星。*

</td>
</tr>
</table>

**一个 prompt，22 个文件自动生成，15 项质量检查通过，零手动操作。**

---

## ⭐ 仓库爆火的 5 个秘密

> 基于高星仓库研究：做到这 5 点的仓库，star 数平均增长 **3-5 倍**。

| # | 策略 | 本 Skill 能做到？ |
|---|------|:---:|
| 1 | **3 秒视觉钩子**（banner、logo、清晰标语） | ✅ 自动生成 SVG |
| 2 | **社会证明前置**（star 数、下载量、"被谁使用"） | ✅ Proof Bar 区块 |
| 3 | **60 秒内上手**（附带预期输出） | ✅ 模板驱动 |
| 4 | **社交预览图**（Twitter/Slack/微信链接预览） | ✅ 1200×630 SVG |
| 5 | **社区信号**（Issue 模板、贡献指南、行为准则） | ✅ 7 个文件自动 |

---

## ⚡ 快速开始

⏱️ **30 秒上手**

```bash
# 安装 — 克隆到 Codex 技能目录
git clone https://github.com/gtskevin/repo-showcase.git ~/.codex/skills/repo-showcase
```

然后在任意项目中对 Codex / Claude Code 说：

```
"发布前帮我美化一下 GitHub 仓库"
```

**预期输出：**
```
🔍 分析仓库中...
   → 类型：NPM 库 (TypeScript)
   → 目标用户：前端开发者
   → 检测到 3 个竞品

📝 生成展示文件...
   → README.md（16 个区块，转化率优化）
   → .github/assets/logo.svg（支持暗色模式）
   → .github/assets/banner.svg（800×200）
   → .github/social-preview.svg（1200×630 og:image）
   → 5 个社区文件

✅ 质量检查：15/15 全部通过
🚀 准备推送！
```

---

## 🎯 支持的仓库类型

| 类型 | 自动检测方式 | 展示重点 |
|------|------------|---------|
| 🤖 **AI Skill** | 存在 `SKILL.md` | 示例 Prompt · 安装命令 · 双读者 |
| 🌐 **Web 应用** | 前端框架配置 | 截图 · 在线 Demo · 部署按钮 |
| 📦 **库** | `package.json` / `pyproject.toml` | 5 分钟上手 · Bundle 大小 · 多包管理器 |
| ⌨️ **CLI 工具** | `bin` 字段 | ASCII art · 命令参考表 |

---

## 🏆 坦诚对比

| 能力 | **Repo Showcase** | readme-ai | Profile README Gen |
|------|:---:|:---:|:---:|
| AI Agent 集成 | ✅ 原生 Skill | ❌ 独立 CLI | ❌ 仅网页 |
| AI Skill 仓库支持 | ✅ 双读者 | ❌ 通用 | ❌ 不支持 |
| SVG 自动生成 | ✅ Logo + Banner + OG | ❌ 纯文字 | ⚠️ 模板 |
| 暗色模式 | ✅ 内置 | ❌ 无 | ❌ 无 |
| 社区文件 | ✅ 7 个模板 | ❌ 无 | ❌ 无 |
| 质量自检 | ✅ 15 项检查 | ❌ 无 | ❌ 无 |
| GitHub SEO | ✅ Topics + About | ❌ 无 | ❌ 无 |
| 独立 CLI 使用 | ❌ 需要 Agent | ✅ 可以 | ✅ 可以 |

> 💡 **选 readme-ai：** 如果你想要独立 CLI 工具，不需要 AI Agent。
> 💡 **选 Repo Showcase：** 如果你用 Codex/Claude Code，想要完整的展示流水线。

---

## ❓ 常见问题

<details>
<summary>🤔 支持 Claude Code 还是只支持 Codex？</summary>

都支持！这是一个标准的 SKILL.md 技能，兼容任何支持 Skills 的 AI 编程 Agent。
</details>

<details>
<summary>🛡️ 会覆盖现有 README 吗？</summary>

覆盖前会询问。你也可以让它"增强"现有 README 而不是替换。
</details>

<details>
<summary>🎨 可以自定义生成的资源吗？</summary>

当然！编辑 `references/` 中的模板，或直接修改生成的 SVG。技能在运行时从模板读取。
</details>

---

## 🤝 参与贡献

欢迎任何形式的贡献！

- 🐛 [报告 Bug](https://github.com/gtskevin/repo-showcase/issues/new?template=bug_report.md)
- 💡 [功能建议](https://github.com/gtskevin/repo-showcase/issues/new?template=feature_request.md)
- 🔧 [Good First Issues](https://github.com/gtskevin/repo-showcase/labels/good%20first%20issue)

---

## ⭐ Star History

如果这个技能帮你节省了时间，请给个 ⭐ — 帮助更多人发现它！

[![Star History Chart](https://api.star-history.com/svg?repos=gtskevin/repo-showcase&type=Date)](https://star-history.com/#gtskevin/repo-showcase&Date)

---

<div align="center">

**Built with ❤️ by [@gtskevin](https://github.com/gtskevin)**

*让每个仓库都闪闪发光 ✨*

[⬆ 回到顶部](#-repo-showcase)

</div>
