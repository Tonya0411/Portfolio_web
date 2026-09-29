# YT.Ocean 个人作品集 | YT.Ocean Portfolio

> 建筑学学生的个人作品集网站

> A personal portfolio website by an architecture student, showcasing physical models, 3D modeling, self-made merch, and artworks.

🌐 **在线访问 / Live**

- GitHub Pages：<https://tonya0411.github.io/Portfolio_web/>
- 腾讯云 CloudBase：<https://ytocean-d8gbvhq5me05c53ab-1497781587.tcloudbaseapp.com/>

## 简介 / About

**中文**：这是 YT.Ocean 的个人作品集，收录了建筑学学习与实践中的代表作品，分三类展示——实体模型、3D 模型、文创与艺术。

**English**: This is YT.Ocean's personal portfolio, collecting representative works from architecture studies and practice, presented in three categories — Physical Models, 3D Models, and Merch & Artworks.

## 功能特性 / Features

- 中英双语切换 / Bilingual (Chinese/English) switching
- 响应式布局 / Responsive layout
- 深蓝星空 + Aurora 极光动态背景 / Starfield + aurora animated background
- 作品分类横向轮播 + 手动拖拽滚动 / Categorized horizontal marquee with drag-to-scroll
- Works 下拉菜单 + 分类子菜单 / Works dropdown with category submenus
- 项目详情页 + 图片灯箱 / Detail pages with image lightbox
- 关于我 + 联系表单 / About + Contact form

## 技术栈 / Tech Stack

- HTML5 · CSS3
- Tailwind CSS（CDN 引入）/ via CDN
- 原生 JavaScript / Vanilla JavaScript
- GSAP 动画 / GSAP animations
- Font Awesome 图标 / Font Awesome icons

## 项目结构 / Project Structure

```
/
├── index.html            # 首页 / Homepage
├── works/                # 17 个详情页 / 17 detail pages
│   ├── work1.html
│   └── …
├── assets.image/         # 本地图片备份（线上走 R2 图床）/ Local image backup (served via R2 CDN)
├── Projects_document.md  # 项目内容清单 / Project content manifest
└── README.md
```

## 本地运行 / Run Locally

无需构建，直接打开 `index.html` 即可；或用静态服务器：

```bash
npx serve .
```

## 部署 / Deployment

- **GitHub Pages**：源为 `main` 分支根目录。
- **腾讯云 CloudBase**：通过 `@cloudbase/cli` 的 `cloudbase hosting deploy` 部署。

## 许可 / License

MIT
