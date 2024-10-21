# @coffic/juice-editor-draw

JuiceEditor 是一个功能强大的编辑器，现已支持画图功能。以下是如何使用该功能的指南。

## 功能特性

- **画图功能**: 允许用户在编辑器中创建和编辑图形。
- **用户友好界面**: 提供直观的工具栏和快捷键。
- **多种图形支持**: 支持矩形、圆形、线条等基本图形。

## 安装

1. 安装包:

   ```bash
   npm i @coffic/juice-editor-draw
   ```

2. 复制构件到项目目录:

   ```bash
   cp -r node_modules/@coffic/juice-editor-draw/dist ./public/draw
   ```

3. 配置编辑器:

   ```typescript
   window.api.setDrawURL('http://localhost:5173/draw')
   ```

## 贡献

欢迎贡献代码！请提交 Pull Request 或报告问题。

## 许可证

本项目采用 MIT 许可证。
