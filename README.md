# 遁甲归一 · 阴使核心 (DunjiaCore-YinShi)

> **“以天文定格，以阴使洞察。逻辑归一，时空无差。”**

**DunjiaCore-YinShi** 是一款集成了高精度天文算法与独创奇门逻辑的排盘引擎。它通过 WebAssembly (WASM) 驱动底层核心，在浏览器端实现秒级的时空能量场建模与“阴使”深度透析。

---

## 🌌 核心逻辑 (Engine Logic)

* **真太阳时定位**：内置 AstroKernel 模块，通过地理经纬度动态校准真太阳时，锁定精准的时空锚点。
* **独创 O(1) 阴使算法**：不同于传统的查表法，本引擎采用 $O(1)$ 复杂度算法实时推演“显局”与“隐局”的对峙关系。
* **深层能量审计**：自动监控空亡、墓库、值符、值使等核心参数，提供基于“阴使”视角的虚实判读。
* **极致秩序布局**：针对 PC 端优化的 600px 严整网格，实现一屏全显，符合断局者的视觉直觉。

---

## 🛠️ 技术规格 (Tech Specs)

* **核心内核**：`DunjiaCore.wasm` (高性能计算引擎)
* **工程构建**：Vite + `vite-plugin-singlefile` 实现极致内联。
* **源码保护**：集成 `javascript-obfuscator` 进行逻辑平坦化混淆，保护独创理法。
* **交付形式**：单文件 HTML (Single-File Distribution)，无服务器依赖。

---

## 🚀 快速开始 (Quick Start)

### 1. 本地开发
```powershell
npm install
npm run dev
2. 生成加密单文件
PowerShell
npm run build
构建后的 dist/index.html 即为加密后的全量版本。

3. GitHub Pages 部署
直接将 dist/index.html 拖入本仓库根目录，并在 Settings -> Pages 中开启服务即可。

📜 免责声明
本系统仅作为传统文化研究与决策辅助工具，结果仅供参考。

作者：Glory Wei (卫光辉)
版本：2026.03.03
