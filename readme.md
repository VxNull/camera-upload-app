# 📸 Web Camera Capture and Upload Tool

## 项目简介

这是一个现代化的开源Web应用，专为简单、灵活的图像捕获和上传而设计。该工具允许用户直接从浏览器使用摄像头拍照，并提供灵活的图片上传和Webhook触发功能。

## 主要特性

- 🎥 **实时摄像头预览**
  - 支持前置摄像头
  - 简单的摄像头启动和拍照操作

- 📸 **灵活的图片捕获**
  - 实时图像预览
  - 高质量JPEG图片捕获
  - 支持移动端和桌面端

- 🌐 **灵活的上传功能**
  - 自定义上传服务器URL
  - 支持局域网内文件上传
  - 友好的上传状态反馈

- 🔗 **独立Webhook触发**
  - 自定义Webhook URL
  - 支持自定义JSON负载
  - 独立的Webhook触发按钮

## 技术栈

- HTML5
- JavaScript
- Tailwind CSS
- 原生WebRTC和Fetch API

## 快速开始

### 直接使用

1. 下载 `index.html` 文件
2. 使用现代浏览器直接打开
3. 允许摄像头权限

### 本地部署

```bash
# 克隆仓库
git clone https://github.com/VxNull/camera-upload-app.git

# 进入项目目录
cd web-camera-upload-tool

# 直接打开 index.html 或使用轻量级服务器
python -m http.server
# 或
npx http-server
```

## 使用说明

1. 点击"启动摄像头"
2. 点击"拍摄照片"捕获图像
3. 在"上传服务器URL"中输入上传地址
4. 点击"上传照片"
5. 可选：在"Webhook URL"中配置回调地址
6. 点击"触发Webhook"

## 浏览器兼容性

- Chrome (桌面/移动)
- Firefox
- Safari
- Edge

## 注意事项

- 需要HTTPS或本地环境
- 需要浏览器摄像头权限
- 服务器需支持跨域资源共享(CORS)

## 贡献指南

1. Fork 仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交变更 (`git commit -m '添加一些令人惊奇的特性'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 许可证

基于 MIT 许可证开源 - 详见 `LICENSE` 文件

## 作者

VxNull - 初始版本

## 致谢

- Tailwind CSS
- WebRTC 标准