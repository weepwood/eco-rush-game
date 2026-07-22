# 迁徙工坊：生态暴走版

一个使用原生 HTML、CSS 和 JavaScript 制作的“自动化 + Roguelite”浏览器试玩版。

## 在线试玩

GitHub Pages：<https://weepwood.github.io/eco-rush-game/>

## 核心玩法

```text
敌人死亡
→ 掉落生物质
→ 无人机自动回收
→ 培育舱自动制造种子
→ 孵化巢自动生产浮游植物
→ 生产成果触发自动扩建
→ 新单位继续击杀敌人
```

玩家只需要：

- 选择蜂群、火力或工业发展方针；
- 每波结束后选择一项 Roguelite 强化；
- 按空格释放“生态爆发”进行全屏清场。

## 本地运行

直接双击 `index.html`，或在项目目录执行：

```bash
python -m http.server 8080
```

随后访问 `http://localhost:8080`。

## 文件结构

```text
eco-rush-game/
├─ .github/workflows/pages.yml
├─ .nojekyll
├─ index.html
├─ style.css
├─ game.js
└─ README.md
```

## 技术特点

- Canvas 2D
- 原生 JavaScript
- 无第三方运行时依赖
- 支持离线运行
- 使用 GitHub Actions 自动部署 GitHub Pages
