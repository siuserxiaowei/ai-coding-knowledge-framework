# AI Coding Knowledge Framework

<!-- SIUSER-REPO-GUIDE:START -->
## Repository Guide

### What This Repository Does

AI 编程知识框架：把 agentic coding、软件工程纪律和提示词工程整理成系统化学习框架。

English summary: AI coding knowledge framework for agentic coding, software engineering discipline, and prompt engineering.

### Online Entry Points

- GitHub repository: https://github.com/siuserxiaowei/ai-coding-knowledge-framework
- Live / GitHub Pages: https://siuserxiaowei.github.io/ai-coding-knowledge-framework/
- Default branch: `main`
- Primary language: `HTML`

### How To Read / Learn This Repository

1. 先读本 README，确认项目目标、在线入口和本地运行方式。
2. 打开上方 Live / GitHub Pages 链接，先从最终效果理解项目。
3. 按仓库目录从入口文件、数据文件、脚本和文档依次阅读。
4. 如果要修改内容，先小范围改动，再运行本 README 中的验证命令。

### Clone This Repository

```bash
git clone https://github.com/siuserxiaowei/ai-coding-knowledge-framework.git
cd ai-coding-knowledge-framework
```

### Run Or View Locally

```bash
python3 -m http.server 8000
```

然后打开 `http://127.0.0.1:8000/`。

### Repository Map

| Path | Purpose |
| --- | --- |
| `README.md` | 项目入口说明，先读这里。 |
| `index.html` | 静态站首页或页面入口。 |
| `assets/` | 图片、样式、字体或页面资源。 |
| `scripts/` | 构建、同步、生成或维护脚本。 |
| `blueprint.html` | 项目文件。 |
| `magazine.html` | 项目文件。 |
| `research.html` | 项目文件。 |

### Maintenance Notes

- Keep this README in sync when the project purpose, live link, or run commands change.
- Prefer small, focused commits when changing code, data, or generated pages.
- Run the relevant build or validation command before publishing changes.
- If this is a generated/static archive, update the source data first, then regenerate the public files.

### Privacy And Safety

- Do not commit API keys, tokens, passwords, cookies, private URLs, or internal account data.
- Keep private source material out of public GitHub Pages output unless it has been explicitly cleared for publication.
- When in doubt, run a quick secret scan such as `rg -n "token|secret|password|access_key|authorization"` before pushing.
<!-- SIUSER-REPO-GUIDE:END -->

<!-- SIUSER-SEO-INTRO:START -->

## 项目介绍 / Project Introduction

**中文介绍**：AI 编程知识框架页面，把工程纪律、上下文管理、验证、协作和工具链原则整理成可分享的网页版本。

**English**: A shareable AI coding knowledge framework covering engineering discipline, context management, verification, collaboration, and toolchain principles.

**SEO 关键词 / SEO Keywords**: AI coding, agentic coding, software engineering, prompt engineering, AI 编程, 工程纪律

<!-- SIUSER-SEO-INTRO:END -->

Static GitHub Pages version of the AI engineering discipline knowledge framework.

## V2 Pages

- `index.html`: version selector and compact 16-source ledger.
- `research.html`: recommended research archive layout.
- `magazine.html`: editorial long-scroll layout.
- `blueprint.html`: engineering blueprint console layout.
- `assets/v2.css`: shared visual system.
- `scripts/build-v2-pages.mjs`: source-of-truth generator for all four pages.

## Validation

- `npx --yes html-validate index.html research.html magazine.html blueprint.html`
- Each page includes 16 source links with `target="_blank"` and `rel="noopener noreferrer"`.
- The generated pages do not include tracking scripts.

<!-- SIUSER-CONTACT:START -->

## 联系我 / Contact

想交流 AI 工具、内容自动化、SEO、私域增长或项目合作，可以扫码加我微信。

For collaboration on AI tools, content automation, SEO, private-domain growth, or product experiments, scan the WeChat QR code below.

<img src="https://raw.githubusercontent.com/siuserxiaowei/siuserxiaowei/main/assets/contact/wechat-qrcode.jpg" width="180" alt="WeChat QR code / 微信二维码" />

**关键词 / Keywords**: AI coding, agentic coding, software engineering, prompt engineering, AI tools, AI automation, GitHub Pages, SEO

<!-- SIUSER-CONTACT:END -->
