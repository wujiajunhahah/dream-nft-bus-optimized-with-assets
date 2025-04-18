# DreamEcho - 梦境 3D 展示

这是一个基于 Three.js 的 3D 模型展示网页应用，用于展示梦境场景中的双层大巴模型。

## 项目描述

这个项目是一个交互式的 3D 模型展示平台，主要展示了一个梦境场景中的双层大巴事故。网页包含以下主要功能：

- 3D 模型实时渲染和交互
- 梦境描述和关键词展示
- 用户互动功能（点赞、关注）
- 响应式设计，支持移动端和桌面端

## 运行说明

### 前置要求

- Python 3.x（用于运行本地服务器）
- 现代浏览器（支持 WebGL）
- 确保以下文件存在于项目根目录：
  - `index.html`
  - `大巴.obj`（3D 模型文件）
  - `dreamecho_logo.png`（logo 图片）
  - `IMG_1141.jpeg`（创作者头像）

### 运行步骤

1. 打开终端，进入项目目录
```bash
cd 项目目录路径
```

2. 启动 Python 本地服务器
```bash
python3 -m http.server 8080
```

3. 在浏览器中访问
```
http://localhost:8080/index.html
```

### 交互说明

- **模型交互**：
  - 左键拖动：旋转视角
  - 右键拖动：平移视角
  - 滚轮：缩放
  - 双击：重置视角

- **界面交互**：
  - 点赞按钮：显示点赞成功提示
  - 关注按钮：显示关注成功提示

## 技术栈

- Three.js - 3D 渲染引擎
- HTML5/CSS3 - 现代网页布局和样式
- JavaScript ES6+ - 交互功能实现

## 注意事项

1. 确保所有资源文件（3D模型、图片等）都在正确的位置
2. 需要通过 HTTP 服务器访问（如上述 Python 服务器），直接打开 HTML 文件可能无法正常加载 3D 模型
3. 如遇到模型加载失败，请检查：
   - 文件名是否正确（包括中文名）
   - 文件路径是否正确
   - 服务器是否正常运行

## 项目结构

```
dream-nft-bus/
├── index.html          # 主页面
├── 大巴.obj            # 3D 模型文件
├── dreamecho_logo.png  # logo图片
├── IMG_1141.jpeg      # 创作者头像
└── README.md          # 说明文档
``` 