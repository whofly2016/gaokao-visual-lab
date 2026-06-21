# Gaokao Visual Lab · 高考可视化实验室

围绕高考核心概念的**交互式可视化 demo**。每个 demo 都是**单文件、零依赖、双击即开**(原生 HTML + Canvas + MathML),只用自绘抽象模型讲清概念。

> Interactive visualizations for core Chinese college-entrance-exam (Gaokao) math & physics concepts. Each demo is a single, dependency-free HTML file — open it directly in any modern browser.

## 在线体验 / Live

GitHub Pages: 见仓库 **Settings → Pages** 启用后的地址(本 README 会在上线后补具体链接)。

本地预览:克隆后用任意静态服务器打开,例如
```bash
python -m http.server 8080
# 浏览器访问 http://localhost:8080/
```
或直接双击 `index.html`。

## Demo 一览

| Demo | 学科 | 内容 |
|---|---|---|
| [导数可视化实验室](./gaokao-derivative-extrema-lab/index.html) | 数学 | 自绘三次函数,拖点看切线随导数变化,单调区间绿/红分段,极值标注 |
| [抛体运动 3D 实验室](./gaokao-projectile-motion-3d/index.html) | 物理 | 伪 3D 透视场景,速度分解(水平匀速 + 竖直匀变速),落点/射程/最大高度预测 |
| [向量投影实验室](./gaokao-vector-projection-lab/index.html) | 数学 | 拖动向量看点乘/投影/夹角;力的分解模式(切向/法向) |

## 技术

- 原生 HTML + JavaScript + Canvas 2D,数学排版用浏览器原生 **MathML**。
- 无构建步骤、无外部依赖、无网络请求、可离线。

## 合规声明 / Compliance

本仓库所有 demo **仅使用自绘抽象函数 / 向量 / 物理参数**做概念可视化,**未复制任何高考原题文字、原卷图片或答案图,不包含任何原卷文件**。本仓库不分发任何受版权保护的试卷资料。

All demos use only self-drawn, abstract models. This repository contains **no** exam papers, original question text, scanned images, or answer keys.

## License

[MIT](./LICENSE)
