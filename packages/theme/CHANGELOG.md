# @sugarat/theme

## 0.1.14
- chore: 主题配置改为继承的方式引入

## 0.1.13
- fix: route support [withBase](https://vitepress.dev/reference/runtime-api#withbase)

## 0.1.12
- fix: 搜索框影响首页样式

## 0.1.11
- chore: 文档内容完善
- feat：内置搜索弹窗UI更新 - 类似algolia（基于 [vue-command-palette](https://github.com/xiaoluoboding/vue-command-palette/blob/main/src/assets/scss/algolia.scss)）
![](https://img.cdn.sugarat.top/mdImg/MTY3OTEyNDM0ODQ4OA==679124348488)

## 0.1.10
- feat: 支持全文搜索（基于 [pagefind](https://pagefind.app/) 实现）
  - `search: 'pagefind'`

## 0.1.9
### Patch Changes
- feat: 支持自定义推荐文章的展示顺序

## 0.1.8
### Patch Changes

- feat: 支持首页文章置顶能力

## 0.1.7

### Patch Changes

- fix: 文章页顶部展示遮挡问题
- fix: 刷新页面评论偶现不展示
- chore: 模板里添加自定义背景图示例
- chore: 更新文档站介绍

## 0.1.6

### Patch Changes

- fix: 最新版 vitepress 首页顶部 Nav 穿透背景图
- fix: 修复 window 路径问题

## 0.1.5

### Patch Changes

- feat: 支持单独使用博客的主题能力但不影响首页布局

## 0.1.4

### Patch Changes

- fix: cover 提取失败

## 0.1.3

### Patch Changes

- fix: 模板启动构建报错

## 0.1.2

### Patch Changes

- fix: 升级 element-plus 版本，解决构建报错
- feat: 追加主题的导出方式 default

## 0.1.1

### Patch Changes

- fix: 没有初始化 git 之前启动报错
- fix: 文章作者信息重复渲染
- chore: 引导文案更新，记录 degit bug 解法
- chore: 包信息修改

## 0.1.0

### Minor Changes

- feat: 完成初版博客主题的开发
- feat: 支持评论
- feat: 支持全局弹窗 Alert
- feat: 支持全局公告 Popover
- feat: 更多见文档 [主题配置](https://theme.sugarat.top/config/frontmatter.html) [全局配置](https://theme.sugarat.top/config/frontmatter.html)