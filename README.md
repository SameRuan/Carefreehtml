### 项目一：智能番茄时钟 (Smart Pomodoro)

```markdown
# 智能番茄时钟 (Smart Pomodoro)

一款基于 Vue3 组合式 API 开发的智能番茄时钟应用，专注于核心逻辑封装、数据持久化与用户体验细节。

## ✨ 项目亮点

- **核心逻辑封装**：使用 Vue3 组合式 API 封装计时器核心逻辑，设计清晰的模块接口与数据流，使代码结构更加清晰、可复用。
- **数据持久化**：通过 localStorage 持久化存储任务数据，确保刷新或关闭页面后数据不丢失，数据保存率达 100%。
- **用户交互与提醒**：集成 WebAudio API 实现计时结束提醒，并配合桌面通知功能，打造多感官的提醒体验，提升用户专注度。
- **极致细节体验**：采用 CSS3 自定义属性配合 `prefers-color-scheme` 实现深色/明亮主题切换及全设备响应式适配，注重每一处交互细节。
- **灵活配置**：支持自定义时长（≤24小时），满足不同场景下的专注需求，组件复用率达 60%。

## 🛠 技术栈

- **前端框架**：Vue3 (组合式 API)、JavaScript
- **基础与样式**：HTML5、CSS3、localStorage
- **浏览器 API**：WebAudio API、Notification API

## 📁 项目结构

```text
src/
├── components/      # 可复用组件 (计时器、任务列表等)
├── composables/     # 组合式 API 逻辑封装 (计时器核心逻辑)
├── assets/          # 静态资源
├── App.vue          # 主应用组件
└── main.js          # 入口文件


### 项目二：中华美食网 (Chinese Food Website)

一个展示中国传统八大菜系及美食文化的前端静态网站项目。项目采用移动端优先策略，通过纯 CSS 实现网页。

## ✨ 项目亮点

- **高保真还原**：独立完成首页及八大菜系共 9 个页面的开发，精准还原设计稿的排版与视觉细节。
- **多设备兼容性**：通过 Chrome DevTools 进行多设备模拟与真机调试，系统排查并解决了主流浏览器（Chrome/Safari/Edge）的兼容性问题，保证跨端展示的一致性。
- **清晰的代码结构**：采用语义化 HTML5 标签构建页面骨架，CSS 采用模块化命名规范，便于后期维护与扩展。

## 🛠 技术栈

- **基础结构**：HTML5 (语义化标签)
- **样式布局**：CSS3、Flexbox、CSS Grid
- **响应式方案**：CSS3 Media Queries (媒体查询)
- **调试工具**：Chrome DevTools

## 📁 项目结构

```text
chinese-food-website/
├── index.html          # 首页 (Home)
├── cuisines/           # 八大菜系页面目录
│   ├── shandong.html   # 鲁菜
│   ├── sichuan.html    # 川菜
│   ├── guangdong.html  # 粤菜
│   ├── jiangsu.html    # 苏菜
│   ├── zhejiang.html   # 浙菜
│   ├── fujian.html     # 闽菜
│   ├── hunan.html      # 湘菜
│   └── anhui.html      # 徽菜
├── css/                # 样式文件
│   ├── reset.css       # 重置默认样式
│   ├── common.css      # 公共样式与变量
│   └── responsive.css  # 响应式断点样式
├── images/             # 图片与静态资源
