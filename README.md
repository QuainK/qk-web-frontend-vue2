# qk-web-frontend-vue2

QuainK 的个人网站

_此工程使用 Vue.js 2.x 开发_

_更新日志请移步至 [CHANGELOG.md](CHANGELOG.md)_

## 环境

- HTML5
- CSS3
- ES6
- Vue.js 2.x
- @vue/cli 4

## 用法

### 1. 安装好必需的依赖

```npm
npm install
```

### 2. 编译成发布版本（dist）

```npm
npm build
```

## 工程

- 静态资源（页面模板、页面图标）

  > /public/

- 主入口

  > /src/main.js
  >
  > /src/App.vue

- 路由

  > /src/router/

- 页面

  > /src/views/

- 公共资源（图片、样式表）

  > /src/assets/

- 公共组件（页面头部尾部）

  > /src/components/

## 结构

网页使用弹性布局 FlexBox，大致分成上中下三大块，头部尾部不变，主体部分使用路由更新视图。

- 头部 header

  - 品牌 brand

  - 导航 menu（router-link）

- 主体 main（router-view）

  - 标题 title

  - 内容 content

- 尾部 footer
