# 句拓 · Syntopo

**Syntopo Reader v0.31** — 二维视觉句法电子阅读器 / Visual Syntax Reader.

将并列、选言、从属与对位等语言结构直观地呈现在阅读排版中，保留原文以供对照。

## 使用

在浏览器打开仓库中的 [`index.html`](./index.html)，或者访问部署完成后的 GitHub Pages 网站。阅读器主体是一个独立 HTML 文件；部分 DOCX、EPUB、PDF 文稿解析依赖可能按需从网络加载。扫描型 PDF 需要 OCR。

## 当前特性

- **视觉句法**：且／或、从属、对立、共享结构与括线排版；原文与结构视图互换
- **阅读辅助**：平滑扫笔、点状线、短句等待和阅读路径高亮
- **交互编辑**：选区标注、原位编辑、容器关系调整、撤销与重做
- **呈现**：中英注记、文稿导入、响应式页面、多种视觉主题

## GitHub Pages

仓库使用 `.github/workflows/deploy.yml` 在 `main` 更新时部署。首次部署需要在 **Settings → Pages → Build and deployment → Source** 选择 **GitHub Actions**。

目前是持续迭代的研究原型，STML 语法尚未完成完整源码解析。
