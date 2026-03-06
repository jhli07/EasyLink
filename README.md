# ⚡ EasyLink

[English](./README_EN.md) | 中文

一个简约的端对端文件传输工具，基于 WebRTC 点对点传输，无需服务器中转。

## ✨ 特性

- 🔗 **点对点传输** - 数据不经过服务器，完全隐私
- 📱 **跨平台** - 支持所有现代浏览器
- 📦 **大文件支持** - 分片传输，理论上无大小限制
- 🔒 **端到端加密** - WebRTC DTLS 加密
- 📱 **QR 配对** - 手机扫码即可连接
- 🎨 **现代 UI** - 简洁美观的界面设计
- 💾 **状态保存** - 自动保存连接历史

## 🚀 快速开始

### 在线使用

访问 GitHub Pages：
```
https://jhli07.github.io/EasyLink/refactor/EasyLink.html
```

### 本地运行

```bash
# 克隆仓库
git clone https://github.com/jhli07/EasyLink.git

# 直接在浏览器打开 refactor/EasyLink.html
# 或使用任意静态服务器
npx serve .
```

## 📖 使用方法

1. **打开页面** - 在两台设备上打开 EasyLink
2. **生成代码** - 点击"刷新代码"生成 5 位设备码
3. **连接设备** - 在另一台设备输入对方的代码，点击连接
4. **传输文件** - 选择文件，点击发送

### QR 配对（手机到电脑）

1. 电脑上打开 EasyLink，显示二维码
2. 手机扫描二维码自动识别设备码
3. 点击连接即可

## 🔧 技术栈

- **PeerJS** - WebRTC 封装库
- **QRCode.js** - 二维码生成
- **原生 JavaScript** - 无框架依赖
- **WebRTC** - 浏览器原生点对点通信

## 📱 浏览器支持

- Chrome / Edge 80+
- Firefox 78+
- Safari 14+
- 移动端浏览器

## ⚠️ 注意事项

- 需要 HTTPS 环境（或 localhost）
- 某些网络环境下可能需要 TURN 中继服务器
- 防火墙可能阻止 P2P 连接

## 📄 许可证

MIT License