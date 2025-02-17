# WebNav Hub - PornNav

# WebNav Hub - LinkHub PornNav导航

[English](#english) | [中文](#中文)

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/bbylw/PicGo@master/20241220015300647.png" alt="WebNav Hub Preview" width="100%">
</div>

<a name="english"></a>

## 🎨 Design Inspiration

This project's UI design and color scheme is directly inspired by Pornhub's iconic black and orange theme. The choice was deliberate, leveraging the instantly recognizable color palette that has become a cultural phenomenon and internet meme, often referenced in various UI design discussions and parodies.

- Primary Theme Color: `#ff9000` (Pornhub Orange)
- Background: `#0d0d0d` (Dark Black)
- Card Background: `#1a1a1a`
- Text: `#ffffff` (White)

## 🌟 Features

### Modern Design

- Responsive grid layout with beautiful cards
- Smooth animations and transitions
- Dark theme with modern color scheme
- Optimized for both desktop and mobile devices

### Technical Improvements

- Container Queries for more precise responsive design
- Modern CSS selectors (`:has()`) for enhanced interactions
- Intersection Observer for optimized scroll performance
- Secure external links with `rel="noopener noreferrer"`

### Performance Optimizations

- Resource preloading and preconnecting
- Optimized Font Awesome loading
- Reduced motion support for accessibility
- Efficient CSS animations with hardware acceleration

### Security Features

- All external links protected with security attributes
- Safe resource loading from CDN
- Content Security Policy ready
- Cross-origin resource protection

## 🚀 Deployment Options

### GitHub Pages Deployment

1. Fork this repository
2. Go to repository Settings > Pages
3. Select main branch as source
4. Your site will be available at `https://[username].github.io/[repo-name]`

### Cloudflare Pages Deployment

1. Connect your GitHub repository to Cloudflare Pages
2. Set build settings:
   - Build command: `N/A` (static site)
   - Build output directory: `/`
3. Deploy and access via Cloudflare's URL

### Custom Domain Setup

1. Register at [dynv6](https://dynv6.com)
2. Add a new domain and configure DNS settings
3. Point domain to your deployment URL
4. Update DNS settings in your deployment platform

## 🛠 Customization

### Adding New Links

Add new links in the appropriate section using this format:

```html
<a class="link-card" href="[URL]" target="_blank" rel="noopener noreferrer">
    <i class="[ICON-CLASS]" aria-hidden="true"></i>
    <h3>[TITLE]</h3>
</a>
```

### Modifying Categories

Categories are defined by `<h2>` elements with the `category-title` class:

```html
<h2 class="category-title" id="[CATEGORY-ID]">[CATEGORY-NAME]</h2>
```

## 📱 Browser Support

- Modern browsers with CSS Grid support
- Fallbacks for older browsers
- Progressive enhancement approach

## 🔒 Security

All external links include security attributes:

- `rel="noopener"`: Prevents `window.opener` exploitation
- `rel="noreferrer"`: Prevents referrer information leakage

## 📄 License

This project is open-source and available under the MIT License.

---

<a name="中文"></a>

## 🎨 设计灵感

本项目的界面设计和配色方案直接借鉴自 Pornhub 的标志性黑橙配色。这是一个刻意的设计选择，利用了这个已成为文化现象和网络模因的即时可识别配色方案，经常在各种 UI 设计讨论和模仿作品中被引用。

- 主题主色：`#ff9000`（Pornhub 橙）
- 背景色：`#0d0d0d`（深黑色）
- 卡片背景：`#1a1a1a`
- 文字颜色：`#ffffff`（白色）

## 🌟 功能特点

### 现代设计

- 响应式网格布局，精美卡片设计
- 流畅的动画和过渡效果
- 现代深色主题配色
- 同时优化桌面和移动设备体验

### 技术改进

- 使用 Container Queries 实现更精确的响应式设计
- 采用现代 CSS 选择器（`:has()`）增强交互体验
- 通过 Intersection Observer 优化滚动性能
- 使用 `rel="noopener noreferrer"` 确保外部链接安全

### 性能优化

- 资源预加载和预连接
- 优化 Font Awesome 加载
- 支持减少动画以提升可访问性
- 硬件加速的高效 CSS 动画

### 安全特性

- 所有外部链接都添加了安全属性
- 安全的 CDN 资源加载
- 支持内容安全策略
- 跨源资源保护

## 🚀 部署选项

### GitHub Pages 部署

1. Fork 本仓库
2. 进入仓库设置 > Pages
3. 选择 main 分支作为源
4. 您的站点将在 `https://[用户名].github.io/[仓库名]` 可用

### Cloudflare Pages 部署

1. 将您的 GitHub 仓库连接到 Cloudflare Pages
2. 设置构建选项：
   - 构建命令：`N/A`（静态站点）
   - 构建输出目录：`/`
3. 部署并通过 Cloudflare 提供的 URL 访问

### 自定义域名设置

1. 在 [dynv6](https://dynv6.com) 注册
2. 添加新域名并配置 DNS 设置
3. 将域名指向您的部署 URL
4. 在部署平台更新 DNS 设置

## 🛠 自定义设置

### 添加新链接

在适当的区域添加新链接，使用以下格式：

```html
<a class="link-card" href="[URL]" target="_blank" rel="noopener noreferrer">
    <i class="[图标类名]" aria-hidden="true"></i>
    <h3>[标题]</h3>
</a>
```

### 修改分类

分类使用带有 `category-title` 类的 `<h2>` 元素定义：

```html
<h2 class="category-title" id="[分类ID]">[分类名称]</h2>
```

## 📱 浏览器支持

- 支持具有 CSS Grid 功能的现代浏览器
- 为旧版浏览器提供降级方案
- 采用渐进增强方法

## 🔒 安全性

所有外部链接都包含安全属性：

- `rel="noopener"`：防止 `window.opener` 漏洞利用
- `rel="noreferrer"`：防止泄露引用来源信息

## 📄 许可证

本项目采用 MIT 许可证开源。

---

Created with ❤️ by AI, enhanced by humans
由 AI 创建，人类优化
