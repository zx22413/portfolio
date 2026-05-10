# portfolio

Source for [lbdog.uk](https://lbdog.uk) — Tsao De-Wei (曹德偉) 的個人 portfolio。

非技術背景的 Solution Architect / AI PM，透過 agentic engineering 主導 production AI 系統開發。

## 結構

```
.
├── index.html              ← Landing
├── about.html              ← 關於
├── brain.html              ← Brain 系統架構
├── mcp-retrospective.html  ← MCP Monitoring Retrospective（旗艦長文）
├── oss.html                ← OSS Extracts (5 個 modules)
├── 404.html
├── favicon.svg
└── en/
    ├── index.html          ← English landing (partial)
    └── mcp-retrospective.html
```

## 部署

Static HTML，沒有 build step。透過 Cloudflare Pages 從 `main` branch 自動部署。

## 本機預覽

```bash
python -m http.server 8765 --directory .
# 然後開 http://localhost:8765
```
