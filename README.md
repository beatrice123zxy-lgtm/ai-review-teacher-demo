# AI 讲评助手 · 教师端 Demo

面试展示用交互原型，包含班级学情、学生干预、分层任务与试点演示看板。

在线体验：https://beatrice123zxy-lgtm.github.io/ai-review-teacher-demo/

## 演示方式

打开网页即可体验，无需登录、安装或配置 API Key。支持桌面和移动端。

建议按照页面右侧引导体验：查看班级学情、定位学生问题、准备讲评和分层任务、查看演示看板。点击「重置演示」可恢复初始数据。

这是使用模拟数据的产品交互 Demo，不连接真实 AI 服务或学校业务系统。操作记录保存在当前浏览器的 localStorage 中，不会在设备之间同步。

## 本地运行与部署

直接打开 `index.html`，或在本目录运行 `python3 -m http.server 8080` 后访问 http://localhost:8080。

本项目是自包含的静态 HTML，无需构建和第三方依赖。GitHub Pages 从 `main` 分支根目录发布；更新 `index.html` 后推送即可自动更新。

原演示地址：https://ai-review-teacher-demo-1105.honest-petal-8221.chatgpt.site
