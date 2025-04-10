# WikiTok - TikTok风格的维基百科浏览器

WikiTok是一个模仿TikTok界面的维基百科文章浏览应用，提供沉浸式的文章浏览体验。

![WikiTok Logo](public/wiki-logo.svg)

## ✨ 功能特性

- 🎨 TikTok风格的卡片式浏览界面
- ♾️ 无限滚动加载随机维基百科文章
- ❤️ 收藏喜欢的文章功能
- 🔍 在收藏文章中搜索
- 📥 导出收藏文章为JSON文件
- 🌍 多语言支持
- 📱 PWA支持，可安装为桌面/移动应用
- 🎨 暗黑模式UI设计

## 🛠️ 技术栈

- [React 18](https://react.dev/) - 前端框架
- [TypeScript](https://www.typescriptlang.org/) - 类型安全的JavaScript
- [Vite](https://vitejs.dev/) - 构建工具
- [TailwindCSS](https://tailwindcss.com/) - 实用优先的CSS框架
- [Lucide Icons](https://lucide.dev/) - 精美图标库
- [Vite PWA Plugin](https://vite-pwa-org.netlify.app/) - PWA支持

## 🚀 快速开始

### 前置要求

- Node.js 18+
- npm/yarn/pnpm/bun

### 安装依赖

```bash
npm install
# 或
yarn
# 或
pnpm install
# 或
bun install
```

### 开发模式

```bash
npm run dev
# 或
yarn dev
# 或
pnpm dev
# 或
bun run dev
```

开发服务器将运行在 [http://localhost:5173](http://localhost:5173)

### 生产构建

```bash
npm run build
# 或
yarn build
# 或
pnpm build
# 或
bun run build
```

构建结果将输出到 `dist` 目录

### 预览生产构建

```bash
npm run preview
# 或
yarn preview
# 或
pnpm preview
# 或
bun run preview
```

## 📂 项目结构

```
frontend/
├── public/            # 静态资源
├── src/
│   ├── assets/        # 静态资源
│   ├── components/    # React组件
│   │   ├── Article.tsx       # 文章卡片组件
│   │   ├── ArticleList.tsx   # 文章列表组件
│   │   ├── LanguageSelector.tsx # 语言选择器
│   │   └── WikiCard.tsx      # 文章卡片UI组件
│   ├── contexts/       # React上下文
│   │   └── LikedArticlesContext.tsx # 收藏文章状态管理
│   ├── hooks/         # 自定义Hook
│   │   ├── useLocalization.ts # 本地化Hook
│   │   └── useWikiArticles.ts # 维基百科数据获取Hook
│   ├── styles/        # CSS样式
│   ├── types/         # TypeScript类型定义
│   ├── App.tsx        # 主应用组件
│   └── main.tsx       # 应用入口
├── vite.config.ts     # Vite配置
├── tsconfig.json      # TypeScript配置
└── package.json       # 项目依赖和脚本
```

## 🤝 贡献指南

欢迎贡献！请遵循以下步骤：

1. Fork项目
2. 创建你的分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
4. 打开Pull Request

## 📜 许可证

[MIT](LICENSE) © [Isaac Gemal](https://github.com/IsaacGemal)

## ☕ 支持作者

如果你喜欢这个项目，可以考虑[请作者喝咖啡](https://buymeacoffee.com/aizk) ☕
