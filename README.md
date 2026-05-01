# Heran / 禾冉 — 个人品牌网站

暗色系 + 微动效 + 大留白的单页个人网站。

## 本地预览

直接在浏览器中打开 `index.html` 即可。

## 部署到 GitHub Pages

1. 创建一个 GitHub 仓库（如 `heran11011.github.io` 或任意名称）
2. 将本目录下的文件推送到仓库：

```bash
git init
git add .
git commit -m "init: personal brand site"
git remote add origin https://github.com/heran11011/heran11011.github.io.git
git branch -M main
git push -u origin main
```

3. 在仓库 Settings → Pages 中选择 `main` 分支，根目录 `/`，保存
4. 等待 1-2 分钟，访问 `https://heran11011.github.io` 即可

## 技术栈

- 纯 HTML + CSS + Vanilla JS
- Google Fonts (Inter + Noto Sans SC)
- Intersection Observer API (滚动动画)
- CSS 动画 (背景渐变 + 卡片交互)
- 零依赖，零框架

## 文件结构

```
├── index.html   # 主页面
├── style.css    # 样式表
└── README.md    # 本文件
```

---

Built with Cola ☕
