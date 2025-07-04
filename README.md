# 图片模板生成器

> 企业内部使用的在线图片模板生成工具，支持图片编辑、文字叠加、多尺寸预览等功能

## 🚀 功能特性

### 1. 图片上传与处理
- ✅ 支持拖拽上传图片文件
- ✅ 支持 JPG、PNG、GIF、WebP 等常见格式
- ✅ 自动压缩转换为 JPG 格式
- ✅ 文件大小限制：10MB
- ✅ 实时预览上传的图片

### 2. 图片编辑功能
- ✅ 可视化裁剪工具
- ✅ 支持拖拽调整裁剪区域
- ✅ 提供快速比例预设（正方形、16:9、3:4）
- ✅ 实时预览编辑效果
- ✅ 可调整裁剪区域大小和位置

### 3. 文字叠加功能
- ✅ 支持多行文字输入
- ✅ 文字颜色自定义（十六进制颜色选择器）
- ✅ 字体大小调节（12px - 72px）
- ✅ 文字对齐方式（左对齐、居中、右对齐）
- ✅ 边距设置（上、右、下、左）
- ✅ 拖拽定位文字位置
- ✅ 实时预览文字效果

### 4. 字体管理
- ✅ 内置系统字体（Arial、Georgia 等）
- ✅ 支持上传自定义字体文件
- ✅ 支持 TTF、OTF、WOFF、WOFF2 格式
- ✅ 字体加载状态反馈

### 5. 多尺寸预览与下载
- ✅ 默认预设尺寸（496×310px、400×400px、800×400px）
- ✅ 自定义尺寸添加功能
- ✅ 自定义尺寸保存（会话内保持）
- ✅ 同时输出多种尺寸预览
- ✅ 单个尺寸下载
- ✅ 批量下载所有尺寸
- ✅ 自动应用文字叠加到所有尺寸

### 6. 用户界面设计
- ✅ Apple 简洁风格设计
- ✅ 白色主题配色
- ✅ 大圆角设计元素
- ✅ 流畅的微动效交互
- ✅ 响应式布局设计
- ✅ 进度指示器引导

## 🛠️ 技术栈

- **前端框架**: Next.js 14 (App Router)
- **UI 库**: React 18 + TypeScript
- **样式方案**: Tailwind CSS
- **动画库**: Framer Motion
- **图标库**: Lucide React
- **文件处理**: React Dropzone
- **颜色选择**: React Colorful
- **Canvas 操作**: HTML5 Canvas API

## 📦 安装与运行

### 环境要求
- Node.js 18.0 或更高版本
- npm 或 yarn 包管理器

### 安装依赖
```bash
npm install
```

### 启动开发服务器
```bash
npm run dev
```

### 构建生产版本
```bash
npm run build
npm start
```

## 📝 使用说明

### 基本工作流程

1. **上传图片**
   - 拖拽图片文件到上传区域
   - 或点击选择文件按钮
   - 系统自动压缩为 JPG 格式

2. **编辑图片**
   - 使用可视化裁剪工具调整图片
   - 拖拽裁剪框改变位置
   - 调整裁剪框大小
   - 应用裁剪效果

3. **添加文字**
   - 输入要叠加的文字内容
   - 选择字体和大小
   - 设置文字颜色和对齐方式
   - 拖拽定位文字位置
   - 调整边距设置

4. **预览与下载**
   - 查看所有尺寸的预览效果
   - 添加自定义输出尺寸
   - 下载单个或全部尺寸图片

## 👥 开发团队

- **项目开发**: AI Assistant
- **技术栈**: Next.js + TypeScript + Tailwind CSS
- **设计风格**: Apple 简洁风格