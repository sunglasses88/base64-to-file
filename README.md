# 📄 Base64 To File Converter (Base64 转文件)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-blue)](https://sunglasses88.github.io/base64-to-file/)

**Base64 To File Converter** 是一个轻量级、安全且高效的在线工具，旨在帮助开发者和普通用户将 Base64 字符串快速还原为原始文件。

🔗 **立即使用：** [https://sunglasses88.github.io/base64-to-file/](https://sunglasses88.github.io/base64-to-file/)

---

## ✨ 核心特性

- **🛡️ 隐私安全**：所有解码与转换逻辑均在浏览器本地完成，数据**绝不上传**到任何服务器，确保敏感文档的安全。
- **👁️ 实时预览**：
  - **PDF 文档**：支持纯 Base64 直接渲染 PDF 预览窗口，无需下载即可查看。
  - **图片格式**：支持 PNG, JPG, GIF 等格式的即时图像显示。
- **🎯 纯 Base64 支持**：自动识别并清洗带有 `data:*/*;base64,` 前缀或纯原始 Base64 编码的字符串。
- **灵活导出**：预设多种常用后缀（PDF, PNG, DOCX 等），并支持自定义任何文件扩展名。
- **📱 响应式设计**：完美适配 PC 和移动端浏览器。

## 🛠️ 使用指南

1. **粘贴数据**：将您的 Base64 字符串粘贴到输入框中。
2. **选择格式**：在下拉菜单中选择目标文件后缀（默认为 PDF）。
3. **即时预览**：如果数据有效，预览窗口将自动显示 PDF 内容或图片。
4. **一键下载**：点击“下载文件”按钮，保存到本地。

## 📂 项目结构

```text
base64-to-file/
├── index.html    # 核心单页面应用 (HTML5 + CSS3 + JS)
├── robots.txt    # SEO 搜索引擎抓取规则
└── README.md     # 项目说明文档