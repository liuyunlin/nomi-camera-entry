# Nomi 相机体验入口

一个为移动端设计的轻量入口页，让用户通过微信扫码进入 **Nomi 相机小程序**。

## 在线体验

访问：[https://liuyunlin.github.io/nomi-camera-entry/](https://liuyunlin.github.io/nomi-camera-entry/)

<p align="center">
  <img src="assets/nomi-miniapp-qr.png" alt="Nomi 相机小程序二维码" width="280" />
</p>

## 为什么做这个页面

小程序二维码需要一个稳定、可分享且对移动端友好的承载页面。本项目使用纯 HTML/CSS 实现，不依赖框架或构建工具，减少加载和维护成本，并通过 GitHub Pages 持续托管。

## 页面设计

- 响应式布局，适配手机和桌面浏览器
- 视觉焦点集中在二维码和操作说明
- 无第三方依赖，无用户数据收集
- 使用 `.nojekyll` 保持静态资源路径稳定

## 项目结构

```text
nomi-camera-entry/
├── index.html                  # 页面结构与样式
├── assets/
│   └── nomi-miniapp-qr.png     # 小程序二维码
├── .nojekyll                   # 跳过 Jekyll 处理
└── README.md
```

## 更新二维码

使用新的图片覆盖 `assets/nomi-miniapp-qr.png`，提交到默认分支后即可更新线上入口。

## 本地预览

```bash
python3 -m http.server 8000
```

然后访问 [http://localhost:8000](http://localhost:8000)。
